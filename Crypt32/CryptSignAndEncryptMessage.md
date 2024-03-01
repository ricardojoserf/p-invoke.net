## CryptSignAndEncryptMessage

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptSignAndEncryptMessage(
   ref CRYPT_SIGN_MESSAGE_PARA pSignPara,
   ref CRYPT_ENCRYPT_MESSAGE_PARA pEncryptPara,
   uint cRecipientCert,
   IntPtr[] rgpRecipientCert,
   byte[] pbToBeSignedAndEncrypted,
   uint cbToBeSignedAndEncrypted,
   byte[] pbSignedAndEncryptedBlob,
   ref uint pcbSignedAndEncryptedBlob
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsignandencryptmessage)
