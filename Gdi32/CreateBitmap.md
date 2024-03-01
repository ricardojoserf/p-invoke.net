## CreateBitmap

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern IntPtr CreateBitmap(
   int nWidth,
   int nHeight,
   uint cPlanes,
   uint cBitsPerPel,
   IntPtr lpvBits
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-createbitmap)
