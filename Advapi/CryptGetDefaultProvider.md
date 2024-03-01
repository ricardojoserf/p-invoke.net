## CryptGetDefaultProvider

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptGetDefaultProvider(
   uint dwProvType,
   ref uint pdwReserved,
   uint dwFlags,
   StringBuilder pszProvName,
   ref uint pcbProvName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetdefaultprovidera)
