## CryptGetKeyParam

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptGetKeyParam(
   IntPtr hKey,
   uint dwParam,
   IntPtr pbData,
   ref uint pdwDataLen,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetkeyparam)
