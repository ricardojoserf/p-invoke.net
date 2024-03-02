## CoFileTimeToDosDateTime

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoFileTimeToDosDateTime(
   ref FILETIME lpFileTime,
   out ushort lpDosDate,
   out ushort lpDosTime
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/objbase/nf-objbase-cofiletimetodosdatetime)
