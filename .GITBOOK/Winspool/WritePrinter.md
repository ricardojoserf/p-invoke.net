## WritePrinter

```csharp
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool WritePrinter(
   IntPtr hPrinter,
   IntPtr pBuf,
   uint cbBuf,
   out uint pcWritten
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/writeprinter)
