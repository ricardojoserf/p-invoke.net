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

Microsoft documentation: (TODO)
