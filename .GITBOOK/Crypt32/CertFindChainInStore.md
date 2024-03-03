## CertFindChainInStore

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertFindChainInStore(
   IntPtr hCertStore,
   uint dwCertEncodingType,
   uint dwFindFlags,
   uint dwFindType,
   IntPtr pvFindPara,
   IntPtr pPrevChainContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certfindchaininstore)
