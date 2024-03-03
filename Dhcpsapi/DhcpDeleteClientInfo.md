## DhcpDeleteClientInfo

```csharp
[DllImport("dhcpsapi.dll", SetLastError = true)]
public static extern uint DhcpDeleteClientInfo(
   IntPtr ServerIpAddress,
   ref DHCP_SEARCH_INFO SearchInfo,
   IntPtr ClientInfo
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/dhcpsapi/nf-dhcpsapi-dhcpdeleteclientinfo)
