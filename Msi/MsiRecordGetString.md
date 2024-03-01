## MsiRecordGetString

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiRecordGetString(
   IntPtr hRecord,
   int iField,
   [MarshalAs(
   UnmanagedType.LPTStr)] StringBuilder szValueBuf,
   ref int pcchValueBuf
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msirecordgetstring)
