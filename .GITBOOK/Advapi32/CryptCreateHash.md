## CryptCreateHash

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CryptCreateHash(
   IntPtr hProv,
   uint Algid,
   IntPtr hKey,
   uint dwFlags,
   out IntPtr phHash
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptcreatehash)
