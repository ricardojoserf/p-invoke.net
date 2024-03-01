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

Microsoft documentation: (TODO)
