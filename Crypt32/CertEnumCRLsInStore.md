## CertEnumCRLsInStore

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertEnumCRLsInStore(
   IntPtr hCertStore,
   IntPtr pPrevCrlContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certenumcrlsinstore)
