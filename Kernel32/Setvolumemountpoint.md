## Setvolumemountpoint

```
[DllImport("Kernel32.dll", CharSet = CharSet.Unicode, SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetVolumeMountPoint(
   string lpszVolumeMountPoint,
   string lpszVolumeName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-setvolumemountpointw)
