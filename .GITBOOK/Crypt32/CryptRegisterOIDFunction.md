## CryptRegisterOIDFunction

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptRegisterOIDFunction(
   uint dwEncodingType,
   string pszFuncName,
   string pszOID,
   string pwszDll,
   string pwszOverrideDll,
   uint dwIndex
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptregisteroidfunction)
