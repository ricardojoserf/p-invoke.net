## DhcpEnumServers

```
[DllImport("dhcpsapi.dll", SetLastError = true)]
public static extern uint DhcpEnumServers(
   uint Flags,
   ref IntPtr Servers,
   ref uint ServersRead,
   ref uint ServersTotal
);
```

Microsoft documentation: (TODO)
