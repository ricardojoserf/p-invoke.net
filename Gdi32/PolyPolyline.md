## PolyPolyline

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool PolyPolyline(
   IntPtr hdc,
   [In] POINT[] apt,
   [In] uint[] acp,
   uint csz
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-polypolyline)
