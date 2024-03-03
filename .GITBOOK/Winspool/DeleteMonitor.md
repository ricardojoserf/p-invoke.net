## DeleteMonitor

```
[DllImport("winspool.drv", SetLastError = true)]
public static extern bool DeleteMonitor(
   IntPtr pName,
   IntPtr pEnvironment,
   IntPtr pMonitorName
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/printdocs/deletemonitor)
