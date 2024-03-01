## CryptVerifyTimeStampSignatureWithProvider

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptVerifyTimeStampSignatureWithProvider(
   byte[] pbTSContentInfo,
   byte[] pbData,
   uint cbData,
   IntPtr hAdditionalStore,
   IntPtr ppSignerCert,
   IntPtr ppTimeStampCert,
   ref IntPtr ppTSTInfo,
   ref uint pdwReserved,
   IntPtr hCryptProv
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptverifytimestampsignaturewithprovider)
