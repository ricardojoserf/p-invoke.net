## CryptGetKeyIdentifierProperty

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptGetKeyIdentifierProperty(
   IntPtr pKeyIdentifierBlob,
   uint dwPropId,
   uint dwFlags,
   byte[] pvData,
   ref uint pcbData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetkeyidentifierproperty)
