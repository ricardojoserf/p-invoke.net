## Lockfile

```
[DllImport("Kernel32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool LockFile(IntPtr hFile,
   uint dwFileOffsetLow,
   uint dwFileOffsetHigh,
   uint nNumberOfBytesToLockLow,
   uint nNumberOfBytesToLockHigh
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-lockfile)
