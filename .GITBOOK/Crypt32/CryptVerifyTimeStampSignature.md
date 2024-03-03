## CryptVerifyTimeStampSignature

```
[DllImport("Crypt32.dll", SetLastError = true)]
public static extern bool CryptVerifyTimeStampSignature(
   byte[] pbTSContentInfo,
   byte[] pbData,
   uint cbData,
   IntPtr hAdditionalStore,
   IntPtr ppSignerCert,
   IntPtr ppTimeStampCert,
   ref IntPtr ppTSTInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wincrypt/nf-wincrypt-cryptverifytimestampsignature)
