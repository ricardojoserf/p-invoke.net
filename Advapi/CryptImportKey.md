## CryptImportKey

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptImportKey(
   IntPtr hProv,
   byte[] pbData,
   uint dwDataLen,
   IntPtr hPubKey,
   uint dwFlags,
   out IntPtr phKey
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptimportkey)
