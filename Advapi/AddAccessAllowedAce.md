## AddAccessAllowedAce

```
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern bool AddAccessAllowedAce(
   IntPtr pAcl,
   uint dwAceRevision,
   uint AccessMask,
   IntPtr pSid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-addaccessallowedace)
