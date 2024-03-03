## SystemTimeToFileTime

```csharp
[DllImport("coredll.dll")]
public static extern void SystemTimeToFileTime(
   ref SYSTEMTIME lpSystemTime,
   out FILETIME lpFileTime
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/timezoneapi/nf-timezoneapi-systemtimetofiletime)
