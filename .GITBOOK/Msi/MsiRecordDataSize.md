## MsiRecordDataSize

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiRecordDataSize(
   IntPtr hRecord,
   [MarshalAs(UnmanagedType.LPTStr)] string szName
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/msiquery/nf-msiquery-msirecorddatasize)
