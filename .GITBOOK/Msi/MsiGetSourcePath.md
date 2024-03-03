## MsiGetSourcePath

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiGetSourcePath(
   IntPtr hProduct,
   [MarshalAs(UnmanagedType.LPTStr)] string szFolder,
   [MarshalAs(UnmanagedType.LPTStr)] StringBuilder lpPathBuf,
   ref int pcchPathBuf
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/msiquery/nf-msiquery-msigetsourcepatha)
