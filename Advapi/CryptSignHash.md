## CryptSignHash

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptSignHash(
   IntPtr hHash,
   uint dwKeySpec,
   string sDescription,
   uint dwFlags,
   byte[] pbSignature,
   ref uint pdwSigLen
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsignhasha)
