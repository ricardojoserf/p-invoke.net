## CryptDuplicateKey

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptDuplicateKey(
   IntPtr hKey,
   IntPtr pdwReserved,
   uint dwFlags,
   out IntPtr phKey
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptduplicatekey)
