## GetPrinterDriverDir

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool GetPrinterDriverDir(
   string pName,
   string pEnvironment,
   uint Level,
   IntPtr pDriverDirectory,
   uint cbBuf,
   out uint pcbNeeded
);
```

[Microsoft documentation](TODO)
