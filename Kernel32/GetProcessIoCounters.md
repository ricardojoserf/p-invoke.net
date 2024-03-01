## GetProcessIoCounters

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetProcessIoCounters(
   IntPtr hProcess,
   out IO_COUNTERS lpIoCounters
);
```

Microsoft documentation: (TODO)
