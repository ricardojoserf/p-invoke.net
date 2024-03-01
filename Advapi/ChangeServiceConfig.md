## ChangeServiceConfig

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ChangeServiceConfig(
   IntPtr hService,
   uint nServiceType,
   uint nStartType,
   uint nErrorControl,
   string lpBinaryPathName,
   string lpLoadOrderGroup,
   IntPtr lpdwTagId,
   [In] char[] lpDependencies,
   string lpServiceStartName,
   string lpPassword,
   string lpDisplayName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-changeserviceconfiga)
