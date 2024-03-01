## InitializeAcl

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool InitializeAcl(
   IntPtr pAcl,
   uint nAclLength,
   uint dwAclRevision
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/aclapi/nf-aclapi-initializeacl)
