## NtSetTimerResolution

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtSetTimerResolution(
   uint DesiredResolution,
   bool SetResolution,
   out uint CurrentResolution
);
```

[Microsoft documentation](TODO)
