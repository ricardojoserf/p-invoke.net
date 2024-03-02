## GetTimeFormat

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.U4)]
public static extern uint GetTimeFormat(
   uint Locale,
   uint dwFlags,
   ref SYSTEMTIME lpTime,
   string lpFormat,
   StringBuilder lpTimeStr,
   int cchTime
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/datetimeapi/nf-datetimeapi-gettimeformata)
