## EnumPrinterDrivers

```csharp
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool EnumPrinterDrivers(
   string pName,
   string pEnvironment,
   uint Level,
   IntPtr pDriverInfo,
   uint cbBuf,
   out uint pcbNeeded,
   out uint pcReturned
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/enumprinterdrivers)
