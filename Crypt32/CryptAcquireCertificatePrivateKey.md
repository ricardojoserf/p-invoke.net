## CryptAcquireCertificatePrivateKey

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptAcquireCertificatePrivateKey(
   IntPtr pCert,
   uint dwFlags,
   IntPtr pvReserved,
   ref IntPtr phCryptProv,
   ref uint pdwKeySpec,
   ref bool pfCallerFreeProv
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptacquirecertificateprivatekey)
