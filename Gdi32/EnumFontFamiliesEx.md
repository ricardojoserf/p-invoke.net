## EnumFontFamiliesEx

```
[DllImport("gdi32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern int EnumFontFamiliesEx(
   IntPtr hdc,
   [In] ref LOGFONT lpLogfont,
   EnumFontFamExProc lpEnumFontFamExProc,
   IntPtr lParam,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-enumfontfamiliesexa)
