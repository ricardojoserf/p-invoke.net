## OpenSCManager

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.SysUInt)]
public static extern IntPtr OpenSCManager(
   string lpMachineName,
   string lpDatabaseName,
   uint dwDesiredAccess
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-openscmanagera)
