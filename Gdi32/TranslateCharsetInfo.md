## TranslateCharsetInfo

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool TranslateCharsetInfo(
   IntPtr src,
   out CHARSETINFO lpCs,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-translatecharsetinfo)
