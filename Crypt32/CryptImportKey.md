## CryptImportKey

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptImportKey(
   IntPtr hProv,
   byte[] pbData,
   uint dwDataLen,
   IntPtr hPubKey,
   uint dwFlags,
   ref IntPtr phKey
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptimportkey)
