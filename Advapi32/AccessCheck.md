## AccessCheck

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool AccessCheck(
   IntPtr pSecurityDescriptor,
   IntPtr hClientToken,
   uint DesiredAccess,
   ref GENERIC_MAPPING GenericMapping,
   ref PRIVILEGE_SET PrivilegeSet,
   ref uint PrivilegeSetLength,
   out uint GrantedAccess,
   out uint AccessStatus
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-accesscheck)
