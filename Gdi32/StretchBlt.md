## StretchBlt

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool StretchBlt(
   IntPtr hdcDest,
   int xDest,
   int yDest,
   int wDest,
   int hDest,
   IntPtr hdcSrc,
   int xSrc,
   int ySrc,
   int wSrc,
   int hSrc,
   uint rop
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-stretchblt)
