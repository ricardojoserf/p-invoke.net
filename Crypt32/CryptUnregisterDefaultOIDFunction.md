## CryptUnregisterDefaultOIDFunction

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptUnregisterDefaultOIDFunction(
   uint dwEncodingType,
   string pszFuncName,
   uint dwIndex
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptunregisterdefaultoidfunction)
