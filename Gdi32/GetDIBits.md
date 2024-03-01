## GetDIBits

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern int GetDIBits(
   IntPtr hdc,
   IntPtr hbm,
   uint start,
   uint cLines,
   [Out] byte[] lpvBits,
   ref BITMAPINFO lpbmi,
   uint usage
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getdibits)
