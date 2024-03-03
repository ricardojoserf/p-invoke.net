## CertCreateCTLContext

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertCreateCTLContext(
   uint dwMsgAndCertEncodingType,
   byte[] pbCtlEncoded,
   uint cbCtlEncoded
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certcreatectlcontext)
