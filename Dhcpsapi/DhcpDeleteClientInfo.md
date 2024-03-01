## DhcpDeleteClientInfo

```
[DllImport("dhcpsapi.dll", SetLastError = true)]
public static extern uint DhcpDeleteClientInfo(
   IntPtr ServerIpAddress,
   ref DHCP_SEARCH_INFO SearchInfo,
   IntPtr ClientInfo
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/dhcpssdk/nf-dhcpssdk-dhcpdeleteclientinfo)
