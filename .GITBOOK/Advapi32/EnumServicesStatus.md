## EnumServicesStatus

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumServicesStatus(
   IntPtr hSCManager,
   uint dwServiceType,
   uint dwServiceState,
   IntPtr lpServices,
   uint cbBufSize,
   out uint pcbBytesNeeded,
   out uint lpServicesReturned,
   out uint lpResumeHandle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-enumservicesstatusa)
