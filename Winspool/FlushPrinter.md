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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-flushprinter)
