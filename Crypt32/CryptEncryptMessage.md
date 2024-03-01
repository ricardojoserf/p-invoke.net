## CryptEncryptMessage

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptEncryptMessage(
   ref CRYPT_ENCRYPT_MESSAGE_PARA pEncryptPara,
   byte[] pbToBeEncrypted,
   uint cbToBeEncrypted,
   byte[] pbEncryptedBlob,
   ref uint pcbEncryptedBlob
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptencryptmessage)
