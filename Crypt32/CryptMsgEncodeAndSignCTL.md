## CryptMsgEncodeAndSignCTL

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptMsgEncodeAndSignCTL(
   uint dwMsgEncodingType,
   IntPtr pCtlInfo,
   IntPtr rgSigners,
   IntPtr rgUnauthAttrs,
   IntPtr pbEncoded,
   ref uint pcbEncoded
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptmsgencodeandsignctl)
