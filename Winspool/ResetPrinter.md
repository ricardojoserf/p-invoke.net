## ResetPrinter

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool ResetPrinter(
   IntPtr hPrinter,
   ref PRINTER_DEFAULTS pDefault
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-resetprintera)
