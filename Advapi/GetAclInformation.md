## GetAclInformation

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetAclInformation(
   IntPtr pAcl,
   ref ACL_SIZE_INFORMATION pAclInformation,
   uint nAclInformationLength,
   ACL_INFORMATION_CLASS dwAclInformationClass
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-getaclinformation)
