## CryptQueryObject

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptQueryObject(
   uint dwObjectType,
   IntPtr pvObject,
   uint dwExpectedContentTypeFlags,
   uint dwExpectedFormatTypeFlags,
   uint dwFlags,
   ref uint pdwMsgAndCertEncodingType,
   ref uint pdwContentType,
   ref uint pdwFormatType,
   IntPtr phCertStore,
   IntPtr phMsg,
   IntPtr ppvContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptqueryobject)
