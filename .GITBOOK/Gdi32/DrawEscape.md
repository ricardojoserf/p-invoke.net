## DrawEscape

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int DrawEscape(
   IntPtr hdc,
   int nEscape,
   int cbInput,
   string lpszInData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-drawescape)
