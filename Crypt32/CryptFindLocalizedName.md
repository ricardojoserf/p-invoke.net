## CryptFindLocalizedName

```csharp
[DllImport("Crypt32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool CryptFindLocalizedName(
   string pwszCryptName,
   ref uint pdwIndex
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptfindlocalizedname)
