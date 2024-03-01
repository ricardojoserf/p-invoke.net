## NetRemoteComputerSupports

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetRemoteComputerSupports(
   string UncServerName,
   uint SupportLevel,
   uint SupportMask
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmapibuf/nf-lmapibuf-netremotecomputersupports)
