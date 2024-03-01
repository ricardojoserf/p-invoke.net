## CryptVerifyTimeStampSignatureForNoChainWithTimeStampArray

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptVerifyTimeStampSignatureForNoChainWithTimeStampArray(
   byte[] pbTSContentInfo,
   byte[] pbData,
   uint cbData,
   IntPtr hAdditionalStore,
   IntPtr ppSignerCert,
   IntPtr ppTimeStampCert,
   uint cTimeStampArray,
   IntPtr rgTimeStampArray,
   ref IntPtr ppTSTInfo,
   ref uint pdwReserved
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptverifytimestampsignaturefornochainwithtimestamparray)
