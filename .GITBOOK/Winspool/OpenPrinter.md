## OpenPrinter

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool OpenPrinter(
   string pPrinterName,
   out IntPtr phPrinter,
   IntPtr pDefault
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/openprinter)
