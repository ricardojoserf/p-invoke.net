## OpenService

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SysUInt)]
public static extern IntPtr OpenService(
   IntPtr hSCManager,
   string lpServiceName,
   uint dwDesiredAccess
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-openservicea)
