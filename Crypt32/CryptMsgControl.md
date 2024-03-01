## CryptMsgControl

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptMsgControl(
   IntPtr hCryptMsg,
   uint dwFlags,
   uint dwCtrlType,
   IntPtr pvCtrlPara
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptmsgcontrol)
