## CryptDecodeObjectEx

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptDecodeObjectEx(
   uint dwCertEncodingType,
   uint lpszStructType,
   byte[] pbEncoded,
   uint cbEncoded,
   uint dwFlags,
   ref CRYPT_DECODE_PARA pDecodePara,
   IntPtr pvStructInfo,
   ref uint pcbStructInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptdecodeobjectex)
