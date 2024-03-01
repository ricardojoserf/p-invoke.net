## SystemTimeToFileTime

```
[DllImport("coredll.dll")]
public static extern void SystemTimeToFileTime(
   ref SYSTEMTIME lpSystemTime,
   out FILETIME lpFileTime
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/sysinfoapi/nf-sysinfoapi-systemtimetofiletime)
