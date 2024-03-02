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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/getprinterdata)
