## SetPrinter

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool SetPrinter(
   IntPtr hPrinter,
   uint Level,
   IntPtr pPrinter,
   uint Command
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/setprinter)
