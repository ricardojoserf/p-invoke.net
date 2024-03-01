## CryptExportKey

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptExportKey(
   IntPtr hKey,
   IntPtr hExpKey,
   uint dwBlobType,
   uint dwFlags,
   byte[] pbData,
   ref uint pcbData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptexportkey)
