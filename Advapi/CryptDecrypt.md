## CryptDecrypt

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptDecrypt(
   IntPtr hKey,
   IntPtr hHash,
   [MarshalAs(UnmanagedType.Bool)] bool Final,
   uint dwFlags,
   IntPtr pbData,
   ref uint pdwDataLen
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptdecrypt)
