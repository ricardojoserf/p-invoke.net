## CryptFormatObject

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptFormatObject(
   uint dwCertEncodingType,
   uint dwFormatType,
   uint dwFormatStrType,
   IntPtr pFormatStruct,
   byte[] lpszFormat,
   ref uint pcbFormat,
   byte[] pbFormat,
   ref uint pcbBytes
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptformatobject)
