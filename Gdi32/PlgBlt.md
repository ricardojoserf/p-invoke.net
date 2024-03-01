## PlgBlt

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool PlgBlt(
   IntPtr hdcDest,
   [In] POINT[] lpPoint,
   IntPtr hdcSrc,
   int xSrc,
   int ySrc,
   int width,
   int height,
   IntPtr hbmMask,
   int xMask,
   int yMask
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-plgblt)
