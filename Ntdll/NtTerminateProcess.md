## NtTerminateProcess

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtTerminateProcess(
   IntPtr ProcessHandle,
   int ExitStatus
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntterminateprocess)
