## CryptSignMessage

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptSignMessage(
   ref CRYPT_SIGN_MESSAGE_PARA pSignPara,
   bool fDetachedSignature,
   uint cToBeSigned,
   IntPtr[] rgpbToBeSigned,
   uint[] rgcbToBeSigned,
   IntPtr pbSignedBlob,
   ref uint pcbSignedBlob
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsignmessage)
