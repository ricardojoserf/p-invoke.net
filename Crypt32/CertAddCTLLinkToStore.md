## CertAddCTLLinkToStore

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CertAddCTLLinkToStore(
   IntPtr hCertStore,
   IntPtr pCtlContext,
   uint dwAddDisposition,
   ref IntPtr ppStoreContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certaddctllinktostore)
