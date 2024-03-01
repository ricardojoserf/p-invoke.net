## GetPrinterDriver

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool GetPrinterDriver(
   IntPtr hPrinter,
   string pEnvironment,
   uint Level,
   IntPtr pDriverInfo,
   uint cbBuf,
   out uint pcbNeeded
);
```

Microsoft documentation: (TODO)
