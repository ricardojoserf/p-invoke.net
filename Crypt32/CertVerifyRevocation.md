## CertVerifyRevocation

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CertVerifyRevocation(
   uint dwEncodingType,
   uint dwRevType,
   uint cContext,
   IntPtr rgpvContext,
   uint dwFlags,
   IntPtr pRevPara,
   ref IntPtr pdwIndex
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-certverifyrevocation)
