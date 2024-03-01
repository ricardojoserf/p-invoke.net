## CryptGenRandom

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptGenRandom(
   IntPtr hProv,
   uint dwLen,
   byte[] pbBuffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgenrandom)
