## XcvData

```csharp
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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/previous-versions/ff564255(v=vs.85))
