## NtSuspendProcess

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtSuspendProcess(
   IntPtr ProcessHandle
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntsuspendprocess)
