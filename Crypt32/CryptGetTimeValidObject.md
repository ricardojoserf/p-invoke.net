## CryptGetTimeValidObject

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptGetTimeValidObject(
   string pszTimeValidOid,
   ref FILETIME pftVerifyTime,
   IntPtr hAdditionalStore,
   uint dwFlags,
   IntPtr pvReserved,
   IntPtr ppValidObject
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptgettimevalidobject)
