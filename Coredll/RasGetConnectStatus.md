## RasGetConnectStatus

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int RasGetConnectStatus(
   IntPtr hrasconn,
   ref RASCONNSTATUS lprasconnstatus
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/rasapi32/nf-rasapi32-rasgetconnectstatusw)
