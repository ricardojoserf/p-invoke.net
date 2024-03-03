## GetPrinter

```csharp
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool GetPrinter(
   IntPtr hPrinter,
   uint Level,
   IntPtr pPrinter,
   uint cbBuf,
   out uint pcbNeeded
);
```

Microsoft documentation: (TODO)
