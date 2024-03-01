## CryptMsgGetParam

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptMsgGetParam(
   IntPtr hCryptMsg,
   uint dwParamType,
   uint dwIndex,
   IntPtr pvData,
   ref uint pcbData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptmsggetparam)
