## GetVolumeInformation

```
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetVolumeInformation(
   string lpRootPathName,
   StringBuilder lpVolumeNameBuffer,
   uint nVolumeNameSize,
   out uint lpVolumeSerialNumber,
   out uint lpMaximumComponentLength,
   out uint lpFileSystemFlags,
   StringBuilder lpFileSystemNameBuffer,
   uint nFileSystemNameSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getvolumeinformationw)
