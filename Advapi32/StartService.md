## StartService

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool StartService(
   IntPtr hService,
   uint dwNumServiceArgs,
   IntPtr lpServiceArgVectors
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsvc/nf-winsvc-startservicea)
