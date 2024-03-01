## CryptGetDefaultProvider

```
[DllImport("Crypt32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool CryptGetDefaultProvider(
   uint dwProvType,
   IntPtr pdwReserved,
   uint dwFlags,
   StringBuilder pszProvName,
   ref uint pcbProvName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetdefaultproviderw)
