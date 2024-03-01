## CryptVerifyDetachedMessageSignature

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptVerifyDetachedMessageSignature(
   ref CRYPT_VERIFY_MESSAGE_PARA pVerifyPara,
   uint dwSignerIndex,
   byte[] pbSignedBlob,
   uint cbSignedBlob,
   uint cToBeSigned,
   IntPtr[] rgpbToBeSigned,
   uint[] rgcbToBeSigned,
   IntPtr ppSignerCert
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptverifydetachedmessagesignature)
