## EnumPrintProcessors

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool EnumPrintProcessors(
   string pName,
   string pEnvironment,
   uint Level,
   IntPtr pPrintProcessorInfo,
   uint cbBuf,
   out uint pcbNeeded,
   out uint pcReturned
);
```

[Microsoft documentation](TODO)
