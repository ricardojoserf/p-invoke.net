## ExtTextOut

```
[DllImport("gdi32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool ExtTextOut(
   IntPtr hdc,
   int X,
   int Y,
   uint fuOptions,
   [In] ref RECT lprc,
   string lpString,
   uint cbCount,
   [In] IntPtr lpDx
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-exttextouta)
