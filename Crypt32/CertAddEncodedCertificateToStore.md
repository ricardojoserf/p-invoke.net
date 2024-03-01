## CertAddEncodedCertificateToStore

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertAddEncodedCertificateToStore(
   IntPtr hCertStore,
   uint dwCertEncodingType,
   byte[] pbCertEncoded,
   uint cbCertEncoded,
   uint dwAddDisposition,
   IntPtr ppCertContext
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certaddencodedcertificatetostore)
