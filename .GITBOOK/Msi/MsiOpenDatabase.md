## MsiOpenDatabase

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiOpenDatabase(
   [MarshalAs(UnmanagedType.LPTStr)] string szDatabasePath,
   IntPtr phPersist,
   out IntPtr phDatabase
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/msiquery/nf-msiquery-msiopendatabasea)
