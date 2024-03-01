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

Microsoft documentation: (TODO)
