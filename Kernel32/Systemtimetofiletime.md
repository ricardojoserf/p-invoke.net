## Systemtimetofiletime

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SystemTimeToFileTime(
   [In] ref SYSTEMTIME lpSystemTime,
   out FILETIME lpFileTime
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-systemtimetofiletime)
