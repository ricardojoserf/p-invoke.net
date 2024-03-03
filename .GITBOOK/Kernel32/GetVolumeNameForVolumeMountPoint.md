## GetVolumeNameForVolumeMountPoint

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetVolumeNameForVolumeMountPoint(
   string lpszVolumeMountPoint,
   StringBuilder lpszVolumeName,
   uint cchBufferLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getvolumenameforvolumemountpointw)
