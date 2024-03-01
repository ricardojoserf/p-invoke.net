## AddMonitor

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool AddMonitor(
   string pName,
   uint Level,
   ref MONITOR_INFO_2 pMonitors
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winspool/nf-winspool-addmonitora)
