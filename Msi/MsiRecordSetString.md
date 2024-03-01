## MsiRecordSetString

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiRecordSetString(
   IntPtr hRecord,
   int iField,
   [MarshalAs(UnmanagedType.LPTStr)] string szValue
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msirecordsetstring)
