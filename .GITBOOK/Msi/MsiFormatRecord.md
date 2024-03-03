## MsiFormatRecord

```csharp
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiFormatRecord(
   IntPtr hInstall,
   IntPtr hRecord,
   [MarshalAs(UnmanagedType.LPTStr)] StringBuilder szResultBuf,
   ref int pcchResultBuf
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/msiquery/nf-msiquery-msiformatrecorda)
