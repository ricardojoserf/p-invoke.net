## CryptInstallDefaultContext

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptInstallDefaultContext(
   IntPtr hCryptProv,
   uint dwDefaultType,
   IntPtr pvDefaultPara,
   uint dwFlags,
   IntPtr pvReserved,
   ref IntPtr phDefaultContext
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptinstalldefaultcontext)
