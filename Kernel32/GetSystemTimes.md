## GetSystemTimes

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetSystemTimes(
   out FILETIME lpIdleTime,
   out FILETIME lpKernelTime,
   out FILETIME lpUserTime
);
```

[Microsoft documentation](TODO)
