## EnumPorts

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool EnumPorts(
   string pName,
   uint Level,
   IntPtr pPort,
   uint cbBuf,
   out uint pcbNeeded,
   out uint pcReturned
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/enumports)
