## NetWkstaGetInfo

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetWkstaGetInfo(
   string ServerName,
   uint Level,
   out IntPtr Buffer
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmwksta/nf-lmwksta-netwkstagetinfo)
