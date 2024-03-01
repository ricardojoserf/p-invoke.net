## PolyDraw

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool PolyDraw(
   IntPtr hdc,
   [In] POINT[] apt,
   [In] byte[] aj,
   int cpt
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-polydraw)
