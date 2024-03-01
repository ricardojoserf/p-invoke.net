## SetSuspendState

```
[DllImport("powrprof.dll", SetLastError = true)]
public static extern bool SetSuspendState(
   bool Hibernate,
   bool ForceCritical,
   bool DisableWakeEvent
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/powrprof/nf-powrprof-setsuspendstate)
