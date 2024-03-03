## FileTimeToSystemTime

```csharp
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FileTimeToSystemTime(
   ref FILETIME lpFileTime,
   out SYSTEMTIME lpSystemTime
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/timezoneapi/nf-timezoneapi-filetimetosystemtime)
