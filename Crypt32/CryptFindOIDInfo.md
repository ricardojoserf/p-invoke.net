## CryptFindOIDInfo

```csharp
[DllImport("Crypt32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool CryptFindOIDInfo(
   uint dwKeyType,
   IntPtr pvKey,
   uint dwGroupId,
   uint dwFlags,
   ref CRYPT_OID_INFO pInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptfindoidinfo)
