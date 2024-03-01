## StgSetTimes

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int StgSetTimes(
   [MarshalAs(
   UnmanagedType.LPWStr)] string lpszName,
   ref FILETIME pctime,
   ref FILETIME patime,
   ref FILETIME pmtime
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ole2/nf-ole2-stgsettimes)
