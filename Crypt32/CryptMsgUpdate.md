## CryptMsgUpdate

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptMsgUpdate(
   IntPtr hCryptMsg,
   byte[] pbData,
   uint cbData,
   bool fFinal
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptmsgupdate)
