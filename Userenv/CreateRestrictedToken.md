## CreateRestrictedToken

```
[DllImport("userenv.dll", SetLastError = true)]
public static extern bool CreateRestrictedToken(
   IntPtr ExistingTokenHandle,
   uint Flags,
   uint DisableSidCount,
   [MarshalAs(
   UnmanagedType.LPArray,
   SizeParamIndex = 2)] SidAndAttributes[] SidsToDisable,
   uint DeletePrivilegeCount,
   [MarshalAs(
   UnmanagedType.LPArray,
   SizeParamIndex = 4)] LuidAndAttributes[] PrivilegesToDelete,
   uint RestrictedSidCount,
   [MarshalAs(
   UnmanagedType.LPArray,
   SizeParamIndex = 6)] SidAndAttributes[] SidsToRestrict,
   out IntPtr NewTokenHandle
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/userenv/nf-userenv-createrestrictedtoken)
