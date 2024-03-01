## AddFontMemResourceEx

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr AddFontMemResourceEx(
   IntPtr pbFont,
   uint cbFont,
   IntPtr pdv,
   [In] ref uint pcFonts
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-addfontmemresourceex)
