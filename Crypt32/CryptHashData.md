## CryptHashData

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptHashData(
   IntPtr hHash,
   byte[] pbData,
   uint dwDataLen,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-crypthashdata)
