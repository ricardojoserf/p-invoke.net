## FindFirstVolume

```csharp
[DllImport("Kernel32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SafeHandle)]
public static extern SafeFindVolumeHandle FindFirstVolume(
   StringBuilder lpszVolumeName,
   uint cchBufferLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-findfirstvolumew)
