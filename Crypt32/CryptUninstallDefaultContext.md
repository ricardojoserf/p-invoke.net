## CryptUninstallDefaultContext

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptUninstallDefaultContext(
   IntPtr hCryptProv,
   uint dwDefaultType,
   IntPtr pvDefaultPara
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptuninstalldefaultcontext)
