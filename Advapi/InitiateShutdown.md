## InitiateShutdown

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool InitiateShutdown(
   string lpMachineName,
   string lpMessage,
   uint dwGracePeriod,
   uint dwShutdownFlags,
   uint dwReason
);
```

Microsoft documentation: (TODO)
