## EnumDependentServices

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumDependentServices(
   IntPtr hService,
   uint dwServiceState,
   IntPtr lpServices,
   uint cbBufSize,
   out uint pcbBytesNeeded,
   out uint lpServicesReturned
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-enumdependentservicesa)
