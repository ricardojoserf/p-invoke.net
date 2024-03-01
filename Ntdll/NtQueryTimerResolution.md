## NtQueryTimerResolution

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtQueryTimerResolution(
   out uint MaximumTime,
   out uint MinimumTime,
   out uint CurrentTime
);
```

[Microsoft documentation](TODO)
