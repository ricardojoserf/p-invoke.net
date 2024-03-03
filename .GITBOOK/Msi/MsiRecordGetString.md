## MsiRecordGetString

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiRecordGetString(
   IntPtr hRecord,
   int iField,
   [MarshalAs(UnmanagedType.LPTStr)] StringBuilder szValueBuf,
   ref int pcchValueBuf
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/msiquery/nf-msiquery-msirecordgetstringa)
