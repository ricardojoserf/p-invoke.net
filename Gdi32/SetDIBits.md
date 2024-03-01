## SetDIBits

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int SetDIBits(
   IntPtr hdc,
   IntPtr hBitmap,
   uint uStartScan,
   uint cScanLines,
   IntPtr lpvBits,
   [In] ref BITMAPINFO lpbmi,
   uint fuColorUse
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setdibits)
