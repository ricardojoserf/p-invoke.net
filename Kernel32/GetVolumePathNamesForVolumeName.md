## GetVolumePathNamesForVolumeName

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetVolumePathNamesForVolumeName(
   string lpszVolumeName,
   StringBuilder lpszVolumePathNames,
   uint cchBufferLength,
   out uint lpcchReturnLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getvolumepathnamesforvolumenamew)
