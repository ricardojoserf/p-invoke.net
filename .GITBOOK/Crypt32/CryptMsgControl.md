## CryptMsgControl

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptMsgControl(
   IntPtr hCryptMsg,
   uint dwFlags,
   uint dwCtrlType,
   IntPtr pvCtrlPara
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptmsgcontrol)
