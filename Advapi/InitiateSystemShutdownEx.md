## InitiateSystemShutdownEx

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool InitiateSystemShutdownEx(
   string lpMachineName,
   string lpMessage,
   uint dwTimeout,
   [MarshalAs(UnmanagedType.Bool)] bool bForceAppsClosed,
   [MarshalAs(UnmanagedType.Bool)] bool bRebootAfterShutdown,
   uint dwReason
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-initiatesystemshutdownexa)
