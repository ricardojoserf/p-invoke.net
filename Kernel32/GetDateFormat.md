## GetDateFormat

```
[DllImport("Kernel32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetDateFormat(
   uint Locale,
   uint dwFlags,
   ref SYSTEMTIME lpDate,
   string lpFormat,
   StringBuilder lpDateStr,
   int cchDate
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-getdateformatw)
