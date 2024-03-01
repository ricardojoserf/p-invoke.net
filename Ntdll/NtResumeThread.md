## NtResumeThread

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtResumeThread(
   IntPtr ThreadHandle,
   out uint SuspendCount
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntresumethread)
