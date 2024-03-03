## ControlService

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ControlService(
   IntPtr hService,
   uint dwControl,
   ref SERVICE_STATUS lpServiceStatus
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-controlservice)
