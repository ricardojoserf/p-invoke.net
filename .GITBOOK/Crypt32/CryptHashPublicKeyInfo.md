## CryptHashPublicKeyInfo

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptHashPublicKeyInfo(
   IntPtr hCryptProv,
   uint Algid,
   uint dwFlags,
   uint dwCertEncodingType,
   ref CRYPTOAPI_BLOB pInfo,
   byte[] pbComputedHash,
   ref uint pcbComputedHash
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-crypthashpublickeyinfo)
