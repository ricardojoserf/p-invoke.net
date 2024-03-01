## CertEnumCertificatesInStore

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertEnumCertificatesInStore(
   IntPtr hCertStore,
   IntPtr pPrevCertContext
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certenumcertificatesinstore)
