## MsiGetFileVersion

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiGetFileVersion(
   [MarshalAs(UnmanagedType.LPTStr)] string szFilePath,
   [MarshalAs(UnmanagedType.LPTStr)] StringBuilder lpVersionBuf,
   ref int pcchVersionBuf,
   [MarshalAs(UnmanagedType.LPTStr)] StringBuilder lpLangBuf,
   ref int pcchLangBuf
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msigetfileversionw)
