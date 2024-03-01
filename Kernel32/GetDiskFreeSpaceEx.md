## GetDiskFreeSpaceEx

```
[DllImport("Kernel32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetDiskFreeSpaceEx(
   string lpDirectoryName,
   out ulong lpFreeBytesAvailableToCaller,
   out ulong lpTotalNumberOfBytes,
   out ulong lpTotalNumberOfFreeBytes
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getdiskfreespaceexw)
