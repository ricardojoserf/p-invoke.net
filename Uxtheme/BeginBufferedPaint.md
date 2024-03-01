## BeginBufferedPaint

```
[DllImport("uxtheme.dll", SetLastError = true)]
public static extern IntPtr BeginBufferedPaint(
   HDC hdcTarget,
   ref RECT prcTarget,
   BP_BUFFERFORMAT dwFormat,
   ref BP_PAINTPARAMS pPaintParams,
   out IntPtr phdc
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/uxtheme/nf-uxtheme-beginbufferedpaint)
