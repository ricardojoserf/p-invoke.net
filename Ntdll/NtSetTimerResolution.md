## NtSetTimerResolution

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtSetTimerResolution(
   uint DesiredResolution,
   bool SetResolution,
   out uint CurrentResolution
);
```

Microsoft documentation: [Link](http://undocumented.ntinternals.net/UserMode/Undocumented%20Functions/Time/NtSetTimerResolution.html)
