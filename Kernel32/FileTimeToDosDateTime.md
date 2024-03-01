## FileTimeToDosDateTime

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FileTimeToDosDateTime(
   ref FILETIME lpFileTime,
   out ushort lpFatDate,
   out ushort lpFatTime
);
```

[Microsoft documentation](TODO)
