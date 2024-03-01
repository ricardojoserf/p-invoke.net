## CryptGetUserKey

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptGetUserKey(
   IntPtr hProv,
   uint dwKeySpec,
   out IntPtr phUserKey
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetuserkey)
