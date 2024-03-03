## CryptMsgCalculateEncodedLength

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptMsgCalculateEncodedLength(
   uint dwMsgEncodingType,
   uint dwFlags,
   uint dwMsgType,
   IntPtr pvMsgEncodeInfo,
   IntPtr pszInnerContentObjID,
   uint cbData,
   ref uint pcbEncoded
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptmsgcalculateencodedlength)
