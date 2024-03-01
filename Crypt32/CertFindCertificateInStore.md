## CertFindCertificateInStore

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertFindCertificateInStore(
   IntPtr hCertStore,
   uint dwCertEncodingType,
   uint dwFindFlags,
   uint dwFindType,
   IntPtr pvFindPara,
   IntPtr pPrevCertContext
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certfindcertificateinstore)
