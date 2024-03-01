## GetVolumePathName

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetVolumePathName(
   string lpszFileName,
   StringBuilder lpszVolumePathName,
   uint cchBufferLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getvolumepathnamew)
