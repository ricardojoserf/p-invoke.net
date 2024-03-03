## DhcpEnumSubnets

```
[DllImport("dhcpsapi.dll", SetLastError = true)]
public static extern uint DhcpEnumSubnets(
   IntPtr ServerIpAddress,
   ref uint ResumeHandle,
   uint PreferredMaximum,
   ref IntPtr SubnetInfo,
   ref uint ElementsRead,
   ref uint ElementsTotal
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/dhcpsapi/nf-dhcpsapi-dhcpenumsubnets)
