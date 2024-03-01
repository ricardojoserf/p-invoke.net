## GetPrinterData

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool GetPrinterData(
   IntPtr hPrinter,
   string pValueName,
   out uint pType,
   IntPtr pData,
   uint nSize,
   out uint pcbNeeded
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-getprinterdataa)
