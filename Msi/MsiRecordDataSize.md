## MsiRecordDataSize

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiRecordDataSize(
   IntPtr hRecord,
   [MarshalAs(UnmanagedType.LPTStr)] string szName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msirecorddatasize)
