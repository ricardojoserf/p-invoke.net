## CertFindCertificateInCRL

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertFindCertificateInCRL(
   IntPtr pCert,
   IntPtr pCrlContext,
   uint dwFlags,
   IntPtr pvReserved,
   IntPtr pRevocationPara,
   ref CRL_FIND_ISSUED_FOR_PARA pIssuedFor
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certfindcertificateincrl)
