## CryptUnregisterOIDFunction

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptUnregisterOIDFunction(
   uint dwEncodingType,
   string pszFuncName,
   string pszOID
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptunregisteroidfunction)
