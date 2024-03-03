## CryptDecryptMessage

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptDecryptMessage(
   ref CRYPT_DECRYPT_MESSAGE_PARA pDecryptPara,
   byte[] pbEncryptedBlob,
   uint cbEncryptedBlob,
   byte[] pbDecrypted,
   ref uint pcbDecrypted,
   ref IntPtr ppXchgCert
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptdecryptmessage)
