## Settimezoneinformation

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetTimeZoneInformation([In] ref TIME_ZONE_INFORMATION lpTimeZoneInformation
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/timezoneapi/nf-timezoneapi-settimezoneinformation)
