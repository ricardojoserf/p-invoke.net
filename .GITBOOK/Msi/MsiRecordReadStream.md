## MsiRecordReadStream

```csharp
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiRecordReadStream(
   IntPtr hRecord,
   int iField,
   byte[] szDataBuf,
   ref int pcbDataBuf
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/msiquery/nf-msiquery-msirecordreadstream)
