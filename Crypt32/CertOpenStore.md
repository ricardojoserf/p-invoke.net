## CertOpenStore

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CertOpenStore(
   uint lpszStoreProvider,
   uint dwEncodingType,
   IntPtr hCryptProv,
   uint dwFlags,
   IntPtr pvPara
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certopenstore)
