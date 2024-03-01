## GetProcessIoCounters

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetProcessIoCounters(
   IntPtr hProcess,
   out IO_COUNTERS lpIoCounters
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/processthreadsapi/nf-processthreadsapi-getprocessiocounters)
