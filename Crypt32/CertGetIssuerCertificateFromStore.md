## CertGetIssuerCertificateFromStore

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertGetIssuerCertificateFromStore(
   IntPtr hCertStore,
   IntPtr pIssuerContext,
   IntPtr pPrevIssuerContext,
   ref uint pdwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certgetissuercertificatefromstore)
