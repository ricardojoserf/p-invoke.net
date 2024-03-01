## NtResumeThread

```
[DllImport("ntdll.dll", SetLastError = true)]
public static extern int NtResumeThread(
   IntPtr ThreadHandle,
   out uint SuspendCount
);
```

[Microsoft documentation](TODO)
