## RasEnumConnections

```csharp
[DllImport("coredll.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int RasEnumConnections(
   ref RASCONN lprasconn,
   ref int lpcb,
   ref int lpcConnections
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ras/nf-ras-rasenumconnectionsa)
