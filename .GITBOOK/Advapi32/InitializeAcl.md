## InitializeAcl

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool InitializeAcl(
   IntPtr pAcl,
   uint nAclLength,
   uint dwAclRevision
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-initializeacl#:~:text=The%20InitializeAcl%20function%20creates%20an,ACL%20before%20you%20use%20it.)
