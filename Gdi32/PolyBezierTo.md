## PolyBezierTo

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool PolyBezierTo(
   IntPtr hdc,
   [In] POINT[] lppt,
   uint cCount
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-polybezierto)
