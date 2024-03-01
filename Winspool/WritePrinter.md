## WritePrinter

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool WritePrinter(
   IntPtr hPrinter,
   IntPtr pBuf,
   uint cbBuf,
   out uint pcWritten
);
```

[Microsoft documentation](TODO)
