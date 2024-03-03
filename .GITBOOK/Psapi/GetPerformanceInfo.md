## GetPerformanceInfo

```
[DllImport("psapi.dll", SetLastError = true)]
public static extern bool GetPerformanceInfo(
   out PERFORMANCE_INFORMATION pPerformanceInformation,
   uint cb
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/psapi/nf-psapi-getperformanceinfo)
