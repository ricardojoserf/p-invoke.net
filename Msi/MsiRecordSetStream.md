## MsiRecordSetStream

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiRecordSetStream(
   IntPtr hRecord,
   int iField,
   [MarshalAs(UnmanagedType.LPTStr)] string szFilePath
);
```

[Microsoft documentation](TODO)
