## InitializeSid

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool InitializeSid(
   IntPtr pSid,
   ref SID_IDENTIFIER_AUTHORITY pIdentifierAuthority,
   byte nSubAuthorityCount
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-initializesid)
