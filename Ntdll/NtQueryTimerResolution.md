## NtQueryTimerResolution

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtQueryTimerResolution(
   out uint MaximumTime,
   out uint MinimumTime,
   out uint CurrentTime
);
```

Microsoft documentation: [Link](http://undocumented.ntinternals.net/UserMode/Undocumented%20Functions/Time/NtQueryTimerResolution.html)
