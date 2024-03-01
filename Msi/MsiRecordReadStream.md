## MsiRecordReadStream

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiRecordReadStream(
   IntPtr hRecord,
   int iField,
   byte[] szDataBuf,
   ref int pcbDataBuf
);
```

[Microsoft documentation](TODO)
