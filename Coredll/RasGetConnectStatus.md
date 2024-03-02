## RasGetConnectStatus

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int RasGetConnectStatus(
   IntPtr hrasconn,
   ref RASCONNSTATUS lprasconnstatus
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ras/nf-ras-rasgetconnectstatusa)
