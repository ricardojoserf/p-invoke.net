## CryptVerifyMessageSignature

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptVerifyMessageSignature(
   ref CRYPT_VERIFY_MESSAGE_PARA pVerifyPara,
   uint dwSignerIndex,
   byte[] pbSignedBlob,
   uint cbSignedBlob,
   byte[] pbDecoded,
   ref uint pcbDecoded,
   IntPtr ppSignerCert
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptverifymessagesignature)
