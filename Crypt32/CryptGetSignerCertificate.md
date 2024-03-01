## CryptGetSignerCertificate

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptGetSignerCertificate(
   IntPtr hCryptMsg,
   uint dwSignerIndex,
   uint dwFlags,
   IntPtr ppSignerCert,
   ref uint pdwSignerCert
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetsignercertificate)
