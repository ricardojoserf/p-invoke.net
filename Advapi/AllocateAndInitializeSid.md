## AllocateAndInitializeSid

```
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern bool AllocateAndInitializeSid(
   [In] ref SID_IDENTIFIER_AUTHORITY pIdentifierAuthority,
   byte nSubAuthorityCount,
   uint nSubAuthority0,
   uint nSubAuthority1,
   uint nSubAuthority2,
   uint nSubAuthority3,
   uint nSubAuthority4,
   uint nSubAuthority5,
   uint nSubAuthority6,
   uint nSubAuthority7,
   out IntPtr pSid
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-allocateandinitializesid)
