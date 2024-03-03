## CryptMsgCountersign

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptMsgCountersign(
   IntPtr hCryptMsg,
   uint dwIndex,
   uint cCountersigners,
   IntPtr rgCountersigners
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptmsgcountersign)
