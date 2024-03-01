## CertGetNameString

```
[DllImport("Crypt32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern uint CertGetNameString(
   IntPtr pCertContext,
   uint dwType,
   uint dwFlags,
   IntPtr pvTypePara,
   StringBuilder pszNameString,
   uint cchNameString
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certgetnamestringa)
