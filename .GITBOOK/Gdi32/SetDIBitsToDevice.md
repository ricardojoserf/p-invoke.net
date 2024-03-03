## SetDIBitsToDevice

```csharp
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int SetDIBitsToDevice(
   IntPtr hdc,
   int xDest,
   int yDest,
   uint w,
   uint h,
   int xSrc,
   int ySrc,
   uint uStartScan,
   uint cScanLines,
   IntPtr lpvBits,
   [In] ref BITMAPINFO lpbmi,
   uint fuColorUse
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setdibitstodevice)
