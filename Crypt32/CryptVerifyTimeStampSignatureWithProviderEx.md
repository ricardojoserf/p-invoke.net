## CryptVerifyTimeStampSignatureWithProviderEx

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptVerifyTimeStampSignatureWithProviderEx(
   byte[] pbTSContentInfo,
   byte[] pbData,
   uint cbData,
   IntPtr hAdditionalStore,
   IntPtr ppSignerCert,
   IntPtr ppTimeStampCert,
   ref IntPtr ppTSTInfo,
   ref uint pdwReserved,
   IntPtr hCryptProv,
   uint dwSignerIndex
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptverifytimestampsignaturewithproviderex)
