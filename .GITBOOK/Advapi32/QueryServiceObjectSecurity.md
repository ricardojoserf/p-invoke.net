## QueryServiceObjectSecurity

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool QueryServiceObjectSecurity(
   IntPtr hService,
   uint dwSecurityInformation,
   byte[] lpSecurityDescriptor,
   uint cbBufSize,
   out uint pcbBytesNeeded
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-queryserviceobjectsecurity)
