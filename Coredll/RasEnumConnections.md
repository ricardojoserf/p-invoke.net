## RasEnumConnections

```
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int RasEnumConnections(
   ref RASCONN lprasconn,
   ref int lpcb,
   ref int lpcConnections
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/rasapi32/nf-rasapi32-rasenumconnectionsw)
