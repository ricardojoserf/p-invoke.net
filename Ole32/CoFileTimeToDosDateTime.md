## CoFileTimeToDosDateTime

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoFileTimeToDosDateTime(
   ref FILETIME lpFileTime,
   out ushort lpDosDate,
   out ushort lpDosTime
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/combaseapi/nf-combaseapi-cofiletimetodosdatetime)
