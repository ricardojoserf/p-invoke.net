## RtlCreateUserThread

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int RtlCreateUserThread(
   IntPtr ProcessHandle,
   IntPtr ThreadSecurityDescriptor,
   bool CreateSuspended,
   int StackZeroBits,
   IntPtr StackReserved,
   IntPtr StackCommit,
   IntPtr StartAddress,
   IntPtr StartParameter,
   out IntPtr ThreadHandle,
   out IntPtr ClientID
);
```

Microsoft documentation: [Link](http://undocumented.ntinternals.net/index.html?page=UserMode%2FUndocumented%20Functions%2FExecutable%20Images%2FRtlCreateUserThread.html)
