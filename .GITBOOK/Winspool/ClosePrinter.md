## ClosePrinter

```csharp
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool ClosePrinter(
   IntPtr hPrinter
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/closeprinter)
