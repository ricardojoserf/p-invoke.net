## CryptRetrieveObjectByUrl

```
[DllImport("Crypt32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool CryptRetrieveObjectByUrl(
   string pszUrl,
   uint dwObjectType,
   uint dwRetrievalFlags,
   uint dwTimeout,
   ref IntPtr ppvObject,
   uint hAsyncRetrieve,
   IntPtr pCredentials,
   IntPtr pvVerify,
   IntPtr pCryptProv,
   IntPtr pAuxInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptretrieveobjectbyurlw)
