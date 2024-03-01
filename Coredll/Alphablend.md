## Alphablend

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool AlphaBlend(
   IntPtr hdcDest,
   int xDest,
   int yDest,
   int cxDest,
   int cyDest,
   IntPtr hdcSrc,
   int xSrc,
   int ySrc,
   int cxSrc,
   int cySrc,
   BLENDFUNCTION blendFunction
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-alphablend)
