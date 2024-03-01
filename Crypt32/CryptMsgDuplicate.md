## CryptMsgDuplicate

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptMsgDuplicate(
   IntPtr hCryptMsg,
   ref IntPtr phCryptMsg
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptmsgduplicate)
