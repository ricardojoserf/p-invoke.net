## QueryServiceConfig2

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool QueryServiceConfig2(
   IntPtr hService,
   uint dwInfoLevel,
   IntPtr lpBuffer,
   uint cbBufSize,
   out uint pcbBytesNeeded
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-queryserviceconfig2a)
