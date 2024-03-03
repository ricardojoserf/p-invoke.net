## MsiGetFileHash

```csharp
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiGetFileHash(
   [MarshalAs(UnmanagedType.LPTStr)] string szFilePath,
   uint dwOptions,
   ref IntPtr phHash
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msigetfilehashw)
