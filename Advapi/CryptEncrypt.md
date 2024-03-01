## CryptEncrypt

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptEncrypt(
   IntPtr hKey,
   IntPtr hHash,
   [MarshalAs(UnmanagedType.Bool)] bool Final,
   uint dwFlags,
   IntPtr pbData,
   ref uint pdwDataLen,
   uint dwBufLen
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptencrypt)
