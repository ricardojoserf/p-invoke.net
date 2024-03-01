## CryptEncodeObject

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptEncodeObject(
   uint dwCertEncodingType,
   uint lpszStructType,
   IntPtr pvStructInfo,
   byte[] pbEncoded,
   ref uint pcbEncoded
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptencodeobject)
