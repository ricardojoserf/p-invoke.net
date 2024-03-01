## CryptVerifySignature

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptVerifySignature(
   IntPtr hHash,
   byte[] pbSignature,
   uint cbSigLen,
   IntPtr hPubKey,
   string sDescription,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptverifysignature)
