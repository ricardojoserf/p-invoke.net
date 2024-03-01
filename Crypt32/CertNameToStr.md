## CertNameToStr

```
[DllImport("Crypt32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern uint CertNameToStr(
   uint dwCertEncodingType,
   ref CERT_NAME_BLOB pName,
   uint dwStrType,
   StringBuilder psz,
   uint csz
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certnametostrw)
