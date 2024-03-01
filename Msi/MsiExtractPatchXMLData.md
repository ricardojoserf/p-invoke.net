## MsiExtractPatchXMLData

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiExtractPatchXMLData(
   [MarshalAs(UnmanagedType.LPTStr)] string szPatchPath,
   IntPtr pvReserved,
   [MarshalAs(UnmanagedType.LPTStr)] StringBuilder lpXmlDataBuf,
   ref int pcchXmlDataBuf
);
```

Microsoft documentation: (TODO)
