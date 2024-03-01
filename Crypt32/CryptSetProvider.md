## CryptSetProvider

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptSetProvider(
   uint dwProvType,
   string pszProvName,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsetproviderw)
