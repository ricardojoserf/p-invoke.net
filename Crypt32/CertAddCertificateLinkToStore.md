## CertAddCertificateLinkToStore

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CertAddCertificateLinkToStore(
   IntPtr hCertStore,
   IntPtr pCertContext,
   uint dwAddDisposition,
   ref IntPtr ppStoreContext
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certaddcertificatelinktostore)
