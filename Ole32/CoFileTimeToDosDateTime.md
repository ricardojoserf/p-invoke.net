## CoFileTimeToDosDateTime

```
[DllImport("ole32.dll", SetLastError = true)]
public static extern int CoFileTimeToDosDateTime(
   ref FILETIME lpFileTime,
   out ushort lpDosDate,
   out ushort lpDosTime
);
```

Microsoft documentation: (TODO)
