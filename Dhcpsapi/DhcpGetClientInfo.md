## DhcpGetClientInfo

```
[DllImport("dhcpsapi.dll", SetLastError = true)]
public static extern uint DhcpGetClientInfo(
   IntPtr ServerIpAddress,
   ref DHCP_SEARCH_INFO SearchInfo,
   IntPtr ClientInfo
);
```

Microsoft documentation: (TODO)
