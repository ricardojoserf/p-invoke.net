## CryptImportPublicKeyInfo

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptImportPublicKeyInfo(
   IntPtr hCryptProv,
   uint dwCertEncodingType,
   ref CERT_PUBLIC_KEY_INFO pInfo,
   ref IntPtr phKey
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptimportpublickeyinfo)
