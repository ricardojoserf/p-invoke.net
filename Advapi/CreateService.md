## CreateService

```
[DllImport("Advapi32.dll", SetLastError = true)]
public static extern IntPtr CreateService(
   IntPtr hSCManager,
   string lpServiceName,
   string lpDisplayName,
   uint dwDesiredAccess,
   uint dwServiceType,
   uint dwStartType,
   uint dwErrorControl,
   string lpBinaryPathName,
   string lpLoadOrderGroup,
   IntPtr lpdwTagId,
   string lpDependencies,
   string lpServiceStartName,
   string lpPassword
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-createservicea)
