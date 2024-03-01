## CryptSetProviderExW

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptSetProviderExW(
   string pszProvName,
   uint dwProvType,
   ref uint pdwReserved,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsetproviderexw)
