## CryptGenKey

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptGenKey(
   IntPtr hProv,
   uint Algid,
   uint dwFlags,
   ref IntPtr phKey
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgenkey)
