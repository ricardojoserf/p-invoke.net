## CertCreateCertificateContext

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertCreateCertificateContext(
   uint dwCertEncodingType,
   byte[] pbCertEncoded,
   uint cbCertEncoded
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certcreatecertificatecontext)
