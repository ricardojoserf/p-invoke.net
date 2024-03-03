## CryptMsgOpenToEncode

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern IntPtr CryptMsgOpenToEncode(
   uint dwMsgEncodingType,
   uint dwFlags,
   uint dwMsgType,
   IntPtr pvMsgEncodeInfo,
   IntPtr pszInnerContentObjID,
   IntPtr pStreamInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptmsgopentoencode)
