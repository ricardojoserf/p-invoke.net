## XcvData

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool XcvData(
   IntPtr hXcv,
   string pszDataName,
   IntPtr pInputData,
   uint cbInputData,
   IntPtr pOutputData,
   uint cbOutputData,
   out uint pcbOutputNeeded,
   out uint pdwStatus
);
```

[Microsoft documentation](TODO)
