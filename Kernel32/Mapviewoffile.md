## Mapviewoffile

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.SysInt)]
public static extern IntPtr MapViewOfFile(
   IntPtr hFileMappingObject,
   uint dwDesiredAccess,
   uint dwFileOffsetHigh,
   uint dwFileOffsetLow,
   UIntPtr dwNumberOfBytesToMap
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/memoryapi/nf-memoryapi-mapviewoffile)
