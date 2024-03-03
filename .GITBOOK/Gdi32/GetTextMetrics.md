## GetTextMetrics

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetTextMetrics(
   IntPtr hdc,
   out TEXTMETRIC lptm
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-gettextmetricsa)
