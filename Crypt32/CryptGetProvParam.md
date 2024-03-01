## CryptGetProvParam

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptGetProvParam(
   IntPtr hProv,
   uint dwParam,
   byte[] pbData,
   ref uint pdwDataLen,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetprovparam)
