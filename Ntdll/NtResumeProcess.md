## NtResumeProcess

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtResumeProcess(
   IntPtr ProcessHandle
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winternl/nf-winternl-ntresumeprocess)
