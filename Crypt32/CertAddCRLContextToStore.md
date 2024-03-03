## CertAddCRLContextToStore

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CertAddCRLContextToStore(
   IntPtr hCertStore,
   IntPtr pCrlContext,
   uint dwAddDisposition,
   ref IntPtr ppStoreContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certaddcrlcontexttostore)
