## NtSetTimerResolution

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtSetTimerResolution(
   uint DesiredResolution,
   bool SetResolution,
   out uint CurrentResolution
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/realtimeapiset/nf-realtimeapiset-ntsettimerresolution)
