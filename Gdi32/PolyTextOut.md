## PolyTextOut

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool PolyTextOut(
   IntPtr hdc,
   [In] POLYTEXT[] pptxt,
   int cStrings
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-polytextouta)
