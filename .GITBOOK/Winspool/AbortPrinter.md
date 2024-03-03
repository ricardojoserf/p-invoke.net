## AbortPrinter

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool AbortPrinter(
   IntPtr hPrinter
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/printing-and-print-spooler-functions#:~:text=The%20AbortPrinter%20function%20deletes%20a,printer%20is%20configured%20for%20spooling.&text=The%20AddPrinter%20function%20adds%20a,printers%20for%20a%20specified%20server.&text=The%20AddPrinterConnection%20function%20adds%20a,printer%20for%20the%20current%20user.)
