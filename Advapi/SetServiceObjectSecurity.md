## SetServiceObjectSecurity

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool SetServiceObjectSecurity(
   IntPtr hService,
   SECURITY_INFORMATION dwSecurityInformation,
   [In] byte[] lpSecurityDescriptor
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-setserviceobjectsecurity)
