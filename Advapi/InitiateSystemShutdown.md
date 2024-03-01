## InitiateSystemShutdown

```
[DllImport("Advapi32.dll", SetLastError = true)][return: MarshalAs(UnmanagedType.Bool)]
public static extern bool InitiateSystemShutdown(
   string lpMachineName,
   string lpMessage,
   uint dwTimeout,
   [MarshalAs(UnmanagedType.Bool)] bool bForceAppsClosed,
   [MarshalAs(UnmanagedType.Bool)] bool bRebootAfterShutdown
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-initiatesystemshutdowna)
