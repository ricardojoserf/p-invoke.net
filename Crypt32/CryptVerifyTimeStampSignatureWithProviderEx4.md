## CryptVerifyTimeStampSignatureWithProviderEx4

```csharp
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptVerifyTimeStampSignatureWithProviderEx4(
   byte[] pbTSContentInfo,
   byte[] pbData,
   uint cbData,
   IntPtr hAdditionalStore,
   IntPtr ppSignerCert,
   IntPtr ppTimeStampCert,
   ref IntPtr ppTSTInfo,
   ref uint pdwReserved,
   IntPtr hCryptProv,
   uint dwSignerIndex,
   uint dwReserved,
   IntPtr hGetSignerCert,
   IntPtr pvReserved
);
```

