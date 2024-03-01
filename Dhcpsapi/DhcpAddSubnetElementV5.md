## DhcpAddSubnetElementV5

```
[DllImport("dhcpsapi.dll", SetLastError = true)]
public static extern uint DhcpAddSubnetElementV5(
   IntPtr ServerIpAddress,
   uint SubnetAddress,
   ref DHCP_SUBNET_ELEMENT_DATA_V5 AddElementInfo
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/dhcpssdk/nf-dhcpssdk-dhcpaddsubnetelementv5)
