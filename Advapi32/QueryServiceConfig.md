## QueryServiceConfig

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool QueryServiceConfig(
   IntPtr hService,
   IntPtr lpServiceConfig,
   uint cbBufSize,
   out uint pcbBytesNeeded
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-queryserviceconfiga)
