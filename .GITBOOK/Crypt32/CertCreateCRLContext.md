## CertCreateCRLContext

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertCreateCRLContext(
   uint dwCertEncodingType,
   byte[] pbCrlEncoded,
   uint cbCrlEncoded
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certcreatecrlcontext)
