## CryptVerifyTimeStampSignatureForNoChainWithTimeStampArrayEx

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptVerifyTimeStampSignatureForNoChainWithTimeStampArrayEx(
   byte[] pbTSContentInfo,
   byte[] pbData,
   uint cbData,
   IntPtr hAdditionalStore,
   IntPtr ppSignerCert,
   IntPtr ppTimeStampCert,
   uint cTimeStampArray,
   IntPtr rgTimeStampArray,
   ref IntPtr ppTSTInfo,
   ref uint pdwReserved,
   uint dwSignerIndex
);
```

