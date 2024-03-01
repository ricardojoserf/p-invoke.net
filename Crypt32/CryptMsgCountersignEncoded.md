## CryptMsgCountersignEncoded

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptMsgCountersignEncoded(
   IntPtr hCryptMsg,
   uint dwIndex,
   uint cCountersigners,
   IntPtr rgCountersigners,
   byte[] pbCountersignature,
   ref uint pcbCountersignature
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptmsgcountersignencoded)
