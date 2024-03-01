## GetTextExtentPoint

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetTextExtentPoint(
   IntPtr hdc,
   string lpString,
   int cbString,
   ref SIZE lpSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-gettextextentpointa)
