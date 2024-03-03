## CertFindCTLInStore

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertFindCTLInStore(
   IntPtr hCertStore,
   uint dwCertEncodingType,
   uint dwFindFlags,
   uint dwFindType,
   IntPtr pvFindPara,
   IntPtr pPrevCtlContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certfindctlinstore)
