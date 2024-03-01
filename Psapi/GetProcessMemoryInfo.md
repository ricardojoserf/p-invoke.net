## GetProcessMemoryInfo

```
[DllImport("psapi.dll", SetLastError = true)]
public static extern bool GetProcessMemoryInfo(
   IntPtr hProcess,
   out PROCESS_MEMORY_COUNTERS ppsmemCounters,
   uint cb
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/psapi/nf-psapi-getprocessmemoryinfo)
