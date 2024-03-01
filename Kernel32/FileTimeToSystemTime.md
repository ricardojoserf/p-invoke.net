## FileTimeToSystemTime

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FileTimeToSystemTime(
   ref FILETIME lpFileTime,
   out SYSTEMTIME lpSystemTime
);
```

[Microsoft documentation](TODO)
