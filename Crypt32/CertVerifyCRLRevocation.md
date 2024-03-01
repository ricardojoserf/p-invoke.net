## CertVerifyCRLRevocation

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CertVerifyCRLRevocation(
   uint dwCertEncodingType,
   IntPtr pCertId,
   uint cCrlInfo,
   IntPtr rgpCrlInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certverifycrlrevocation)
