## MaskBlt

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool MaskBlt(
   IntPtr hdcDest,
   int xDest,
   int yDest,
   int width,
   int height,
   IntPtr hdcSrc,
   int xSrc,
   int ySrc,
   IntPtr hbmMask,
   int xMask,
   int yMask,
   uint rop
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-maskblt)
