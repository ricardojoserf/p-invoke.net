## CryptGetUserKey

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptGetUserKey(
   IntPtr hProv,
   uint dwKeySpec,
   ref IntPtr phUserKey
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetuserkey)
