## FlushPrinter

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool FlushPrinter(
   IntPtr hPrinter,
   IntPtr pBuf,
   uint cbBuf,
   out uint pcWritten,
   uint cSleep
);
```

[Microsoft documentation](TODO)
