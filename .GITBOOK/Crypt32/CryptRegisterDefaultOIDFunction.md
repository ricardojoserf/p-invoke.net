## CryptRegisterDefaultOIDFunction

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptRegisterDefaultOIDFunction(
   uint dwEncodingType,
   IntPtr pszFuncName,
   uint dwIndex,
   IntPtr pwszDll
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptregisterdefaultoidfunction)
