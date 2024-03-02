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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/dhcpsapi/nf-dhcpsapi-dhcpenumservers)
