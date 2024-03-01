## EnumFontFamilies

```
[DllImport("gdi32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern int EnumFontFamilies(
   IntPtr hdc,
   string lpszFamily,
   EnumFontFamExProc lpEnumFontFamExProc,
   IntPtr lParam
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-enumfontfamiliesa)
