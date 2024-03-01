## MsiGetFileSignatureInformation

```
[DllImport("msi.dll", CharSet = CharSet.Auto)]
public static extern int MsiGetFileSignatureInformation(
   [MarshalAs(UnmanagedType.LPTStr)] string szSignedObject,
   uint dwFlags,
   ref IntPtr phSignedData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/msi/nf-msi-msigetfilesignatureinformationw)
