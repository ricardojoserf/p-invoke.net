## CryptDecodeObject

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptDecodeObject(
   uint dwCertEncodingType,
   uint lpszStructType,
   byte[] pbEncoded,
   uint cbEncoded,
   uint dwFlags,
   IntPtr pvStructInfo,
   ref uint pcbStructInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptdecodeobject)
