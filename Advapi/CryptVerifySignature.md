## CryptVerifySignature

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptVerifySignature(
   IntPtr hHash,
   byte[] pbSignature,
   uint dwSigLen,
   IntPtr hPubKey,
   string sDescription,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptverifysignaturea)
