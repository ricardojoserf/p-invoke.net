## GetTimeZoneInformation

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetTimeZoneInformation(
   out TIME_ZONE_INFORMATION lpTimeZoneInformation
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/timezoneapi/nf-timezoneapi-gettimezoneinformation)
