## SetNamedSecurityInfo

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint SetNamedSecurityInfo(
   string pObjectName,
   SE_OBJECT_TYPE ObjectType,
   SECURITY_INFORMATION SecurityInfo,
   byte[] psidOwner,
   byte[] psidGroup,
   IntPtr pDacl,
   IntPtr pSacl
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-setnamedsecurityinfoa)
