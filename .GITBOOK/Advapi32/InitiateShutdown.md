## InitiateShutdown

```csharp
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool InitiateShutdown(
   string lpMachineName,
   string lpMessage,
   uint dwGracePeriod,
   uint dwShutdownFlags,
   uint dwReason
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/hyperv_v2/msvm-shutdowncomponent-initiateshutdown)
