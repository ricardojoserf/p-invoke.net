## FindNextVolume

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FindNextVolume(
   SafeFindVolumeHandle hFindVolume,
   StringBuilder lpszVolumeName,
   uint cchBufferLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-findnextvolumew)
