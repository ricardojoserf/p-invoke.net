## CryptInstallOIDFunctionAddress

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptInstallOIDFunctionAddress(
   IntPtr hModule,
   uint dwEncodingType,
   IntPtr wszDll,
   uint cFuncEntry,
   ref CRYPT_OID_FUNC_ENTRY rgFuncEntry
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptinstalloidfunctionaddress)
