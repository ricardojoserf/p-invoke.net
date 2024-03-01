## NtTerminateThread

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtTerminateThread(
   IntPtr ThreadHandle,
   int ExitStatus
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntterminatethread)
