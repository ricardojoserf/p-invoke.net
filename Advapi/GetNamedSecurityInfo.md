## GetNamedSecurityInfo

```
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern uint GetNamedSecurityInfo(
   string pObjectName,
   SE_OBJECT_TYPE ObjectType,
   SECURITY_INFORMATION SecurityInfo,
   out IntPtr pSidOwner,
   out IntPtr pSidGroup,
   out IntPtr pDacl,
   out IntPtr pSacl,
   out IntPtr pSecurityDescriptor
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-getnamedsecurityinfoa)
