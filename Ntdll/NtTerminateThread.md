## NtTerminateThread

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtTerminateThread(
   IntPtr ThreadHandle,
   int ExitStatus
);
```

[Microsoft documentation](TODO)
