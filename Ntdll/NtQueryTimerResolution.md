## NtQueryTimerResolution

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtQueryTimerResolution(
   out uint MaximumTime,
   out uint MinimumTime,
   out uint CurrentTime
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/realtimeapiset/nf-realtimeapiset-ntquerytimerresolution)
