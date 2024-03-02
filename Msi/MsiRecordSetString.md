## MsiRecordSetString

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiRecordSetString(
   IntPtr hRecord,
   int iField,
   [MarshalAs(UnmanagedType.LPTStr)] string szValue
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/msiquery/nf-msiquery-msirecordsetstringa)
