## SetNamedSecurityInfoW

```
[DllImport("Advapi32.dll", SetLastError = true, CharSet = CharSet.Unicode)][return: MarshalAs(UnmanagedType.U4)]
public static extern uint SetNamedSecurityInfoW(
   string pObjectName,
   SE_OBJECT_TYPE ObjectType,
   SECURITY_INFORMATION SecurityInfo,
   byte[] psidOwner,
   byte[] psidGroup,
   IntPtr pDacl,
   IntPtr pSacl
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-setnamedsecurityinfow)
