## SetPrinterData

```csharp
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool SetPrinterData(
   IntPtr hPrinter,
   string pValueName,
   uint Type,
   IntPtr pData,
   uint cbData
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/setprinterdata)
