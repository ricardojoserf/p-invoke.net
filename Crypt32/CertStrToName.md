## CertStrToName

```
[DllImport("Crypt32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool CertStrToName(
   uint dwCertEncodingType,
   string pszX500,
   uint dwStrType,
   IntPtr pvReserved,
   byte[] pbEncoded,
   ref uint pcbEncoded,
   ref IntPtr ppName,
   ref uint pcParsed
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certstrtonamew)
