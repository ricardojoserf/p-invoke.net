## QueryServiceStatus

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool QueryServiceStatus(
   IntPtr hService,
   ref SERVICE_STATUS lpServiceStatus
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-queryservicestatus)
