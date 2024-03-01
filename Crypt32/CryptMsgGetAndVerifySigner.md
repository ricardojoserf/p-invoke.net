## CryptMsgGetAndVerifySigner

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptMsgGetAndVerifySigner(
   IntPtr hCryptMsg,
   uint cSignerStore,
   IntPtr[] rghSignerStore
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptmsggetandverifysigner)
