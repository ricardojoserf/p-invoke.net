## NtTerminateProcess

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtTerminateProcess(
   IntPtr ProcessHandle,
   int ExitStatus
);
```

Microsoft documentation: (TODO)
