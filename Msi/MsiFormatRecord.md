## MsiFormatRecord

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiFormatRecord(
   IntPtr hInstall,
   IntPtr hRecord,
   [MarshalAs(
   UnmanagedType.LPTStr)] StringBuilder szResultBuf,
   ref int pcchResultBuf
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msiformatrecordw)
