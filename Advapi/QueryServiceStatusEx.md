## QueryServiceStatusEx

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool QueryServiceStatusEx(
   IntPtr hService,
   uint InfoLevel,
   IntPtr lpBuffer,
   uint cbBufSize,
   out uint pcbBytesNeeded
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-queryservicestatusex)
