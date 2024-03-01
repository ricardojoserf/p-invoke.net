## WTSTerminateProcess

```
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern bool WTSTerminateProcess(
   IntPtr hServer,
   int ProcessId,
   int ExitCode
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsterminateprocess)
