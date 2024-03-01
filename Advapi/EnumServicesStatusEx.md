## EnumServicesStatusEx

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumServicesStatusEx(
   IntPtr hSCManager,
   uint InfoLevel,
   uint dwServiceType,
   uint dwServiceState,
   IntPtr lpServices,
   uint cbBufSize,
   out uint pcbBytesNeeded,
   ref uint lpServicesReturned,
   ref uint lpResumeHandle,
   string pszGroupName,
   string pszDependencies
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-enumservicesstatusexa)
