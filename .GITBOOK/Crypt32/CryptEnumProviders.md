## CryptEnumProviders

```
[DllImport("Crypt32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool CryptEnumProviders(
   uint dwIndex,
   IntPtr pdwReserved,
   uint dwFlags,
   ref uint pdwProvType,
   StringBuilder pszProvName,
   ref uint pcbProvName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptenumprovidersw)
