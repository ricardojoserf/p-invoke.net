## DosDateTimeToFileTime

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DosDateTimeToFileTime(ushort wFatDate, ushort wFatTime, out FILETIME lpFileTime);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/minwinbase/nf-minwinbase-dosdatetimetofiletime)
