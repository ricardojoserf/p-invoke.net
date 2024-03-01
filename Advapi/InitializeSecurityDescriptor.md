## InitializeSecurityDescriptor

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool InitializeSecurityDescriptor(
   IntPtr pSecurityDescriptor,
   uint dwRevision
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/securitybaseapi/nf-securitybaseapi-initializesecuritydescriptor)
