## CryptSetKeyIdentifierProperty

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptSetKeyIdentifierProperty(
   IntPtr pKeyIdentifierBlob,
   uint dwPropId,
   uint dwFlags,
   byte[] pvData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptsetkeyidentifierproperty)
