## CertEnumCTLsInStore

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertEnumCTLsInStore(
   IntPtr hCertStore,
   IntPtr pPrevCtlContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certenumctlsinstore)
