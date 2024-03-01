## CertRDNValueToStr

```
[DllImport("Crypt32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool CertRDNValueToStr(
   uint dwValueType,
   ref CERT_RDN_VALUE_BLOB pValue,
   StringBuilder psz,
   ref uint pcch
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certrdnvaluetostrw)
