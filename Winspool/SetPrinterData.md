## SetPrinterData

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool SetPrinterData(
   IntPtr hPrinter,
   string pValueName,
   uint Type,
   IntPtr pData,
   uint cbData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-setprinterdataa)
