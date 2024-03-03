## CryptGetHashParam

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptGetHashParam(
   IntPtr hHash,
   uint dwParam,
   byte[] pbData,
   ref uint pdwDataLen,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgethashparam)
