## DosDateTimeToFileTime

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DosDateTimeToFileTime(
   ushort wFatDate,
   ushort wFatTime,
   out FILETIME lpFileTime
);
```

[Microsoft documentation](TODO)
