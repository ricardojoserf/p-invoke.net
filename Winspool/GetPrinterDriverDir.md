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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-getprinterdriverdirectorya)
