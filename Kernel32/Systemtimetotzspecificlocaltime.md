## Systemtimetotzspecificlocaltime

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SystemTimeToTzSpecificLocalTime(IntPtr lpTimeZoneInformation,
   [In] ref SYSTEMTIME lpUniversalTime,
   out SYSTEMTIME lpLocalTime
);
```

Microsoft documentation: (TODO)
