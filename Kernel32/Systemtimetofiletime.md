## Systemtimetofiletime

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SystemTimeToFileTime([In] ref SYSTEMTIME lpSystemTime,
   out FILETIME lpFileTime
);
```

[Microsoft documentation](TODO)
