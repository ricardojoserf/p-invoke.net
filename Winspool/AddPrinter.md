## AddPrinter

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool AddPrinter(
   string pName,
   uint Level,
   ref PRINTER_INFO_1 pPrinter
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-addprintera)
