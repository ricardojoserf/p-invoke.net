## CryptVerifyTimeStampSignatureWithTimeStampArrayEx

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptVerifyTimeStampSignatureWithTimeStampArrayEx(
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

Microsoft documentation: (TODO)
