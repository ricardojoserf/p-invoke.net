## SetBitmapDimensionEx

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool SetBitmapDimensionEx(
   IntPtr hBitmap,
   int w,
   int h,
   out SIZE lpsize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setbitmapdimensionex)
