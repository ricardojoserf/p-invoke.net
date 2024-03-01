## EnumFonts

```
[DllImport("gdi32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern int EnumFonts(
   IntPtr hdc,
   string lpFaceName,
   EnumFontProc lpFontFunc,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-enumfontsa)
