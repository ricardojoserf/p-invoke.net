## DhcpEnumSubnetClients

```
[DllImport("dhcpsapi.dll", SetLastError = true)]
public static extern uint DhcpEnumSubnetClients(
   IntPtr ServerIpAddress,
   uint SubnetAddress,
   ref IntPtr ResumeHandle,
   uint PreferredMaximum,
   ref IntPtr ClientInfo,
   ref uint ElementsRead,
   ref uint ElementsTotal
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/dhcpsapi/nf-dhcpsapi-dhcpenumsubnetclients)
