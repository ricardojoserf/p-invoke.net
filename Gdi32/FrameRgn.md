## FrameRgn

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool FrameRgn(
   IntPtr hdc,
   IntPtr hrgn,
   IntPtr hbr,
   int nWidth,
   int nHeight
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-framergn)
