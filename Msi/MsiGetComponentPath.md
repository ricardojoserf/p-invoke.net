## MsiGetComponentPath

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiGetComponentPath(
   [MarshalAs(UnmanagedType.LPTStr)] string szProduct,
   [MarshalAs(UnmanagedType.LPTStr)] string szComponent,
   [MarshalAs(UnmanagedType.LPTStr)] StringBuilder lpPathBuf,
   ref int pcchBuf
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msigetcomponentpathw)
