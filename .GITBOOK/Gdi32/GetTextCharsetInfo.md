## GetTextCharsetInfo

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int GetTextCharsetInfo(
   IntPtr hdc,
   ref FONTSIGNATURE lpSig,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-gettextcharsetinfo)
