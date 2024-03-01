## CertFindCRLInStore

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertFindCRLInStore(
   IntPtr hCertStore,
   uint dwCertEncodingType,
   uint dwFindFlags,
   uint dwFindType,
   IntPtr pvFindPara,
   IntPtr pPrevCrlContext
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certfindcrlinstore)
