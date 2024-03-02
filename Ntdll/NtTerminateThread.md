## NtTerminateThread

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtTerminateThread(
   IntPtr ThreadHandle,
   int ExitStatus
);
```

Microsoft documentation: [Link](http://undocumented.ntinternals.net/UserMode/Undocumented%20Functions/NT%20Objects/Thread/NtTerminateThread.html)
