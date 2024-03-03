## CryptMsgSignCTL

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptMsgSignCTL(
   uint dwMsgEncodingType,
   IntPtr pbCtlContent,
   uint cbCtlContent,
   IntPtr pSignerCertInfo,
   uint dwSignerIndex,
   IntPtr rgSignerCert,
   IntPtr rgCrl,
   IntPtr pbEncoded,
   ref uint pcbEncoded
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptmsgsignctl)
