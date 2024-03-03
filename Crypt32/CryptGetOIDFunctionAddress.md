## CryptGetOIDFunctionAddress

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptGetOIDFunctionAddress(
   IntPtr hFuncSet,
   uint dwEncodingType,
   IntPtr pszOID,
   uint dwFlags,
   ref IntPtr phFuncAddr,
   ref IntPtr pvFuncAddr,
   ref IntPtr pcbFuncAddr
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgetoidfunctionaddress)
