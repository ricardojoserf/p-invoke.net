## GetDiskFreeSpace

```csharp
[DllImport("Kernel32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetDiskFreeSpace(
   string lpRootPathName,
   out uint lpSectorsPerCluster,
   out uint lpBytesPerSector,
   out uint lpNumberOfFreeClusters,
   out uint lpTotalNumberOfClusters
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-getdiskfreespacew)
