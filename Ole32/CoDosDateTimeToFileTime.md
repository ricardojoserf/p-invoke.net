## CoDosDateTimeToFileTime

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoDosDateTimeToFileTime(
   ushort nDosDate,
   ushort nDosTime,
   out FILETIME lpFileTime
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-codosdatetimetofiletime)
