## PolyPolygon

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool PolyPolygon(
   IntPtr hdc,
   [In] POINT[] apt,
   [In] int[] acp,
   int cPoly
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-polypolygon)
