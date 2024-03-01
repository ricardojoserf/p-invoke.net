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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-xcvdata)
