## CryptMsgOpenToDecode

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CryptMsgOpenToDecode(
   uint dwMsgEncodingType,
   uint dwFlags,
   uint dwMsgType,
   IntPtr hCryptProv,
   IntPtr pRecipientInfo,
   IntPtr pStreamInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptmsgopentodecode)
