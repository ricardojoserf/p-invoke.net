## OpenPrinter

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool OpenPrinter(
   string pPrinterName,
   out IntPtr phPrinter,
   IntPtr pDefault
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-openprintera)
