## Systemtimetofiletime

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SystemTimeToFileTime([In] ref SYSTEMTIME lpSystemTime,
   out FILETIME lpFileTime
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/timezoneapi/nf-timezoneapi-systemtimetofiletime)
