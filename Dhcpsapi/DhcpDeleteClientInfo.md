## DhcpDeleteClientInfo

```
[DllImport("dhcpsapi.dll", SetLastError = true)]
public static extern uint DhcpDeleteClientInfo(
   IntPtr ServerIpAddress,
   ref DHCP_SEARCH_INFO SearchInfo,
   IntPtr ClientInfo
);
```

Microsoft documentation: (TODO)
