## CryptDeriveKey

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptDeriveKey(
   IntPtr hProv,
   uint Algid,
   IntPtr hBaseData,
   uint dwFlags,
   out IntPtr phKey
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptderivekey)
