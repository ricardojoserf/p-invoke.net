## NtResumeThread

```csharp
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtResumeThread(
   IntPtr ThreadHandle,
   out uint SuspendCount
);
```

Microsoft documentation: [Link](http://undocumented.ntinternals.net/UserMode/Undocumented%20Functions/NT%20Objects/Thread/NtResumeThread.html)
