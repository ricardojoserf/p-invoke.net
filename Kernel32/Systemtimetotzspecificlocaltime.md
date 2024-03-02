## Systemtimetotzspecificlocaltime

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SystemTimeToTzSpecificLocalTime(IntPtr lpTimeZoneInformation,
   [In] ref SYSTEMTIME lpUniversalTime,
   out SYSTEMTIME lpLocalTime
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/timezoneapi/nf-timezoneapi-systemtimetotzspecificlocaltime)
