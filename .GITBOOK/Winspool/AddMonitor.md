## AddMonitor

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool AddMonitor(
   string pName,
   uint Level,
   ref MONITOR_INFO_2 pMonitors
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/addmonitor)
