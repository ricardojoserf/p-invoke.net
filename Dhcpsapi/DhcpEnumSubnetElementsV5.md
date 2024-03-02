## DhcpEnumSubnetElementsV5

```
[DllImport("dhcpsapi.dll", SetLastError = true)]
public static extern uint DhcpEnumSubnetElementsV5(
   IntPtr ServerIpAddress,
   uint SubnetAddress,
   uint EnumElementType,
   ref IntPtr ResumeHandle,
   uint PreferredMaximum,
   ref IntPtr EnumElementInfo,
   ref uint ElementsRead,
   ref uint ElementsTotal
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/dhcpsapi/nf-dhcpsapi-dhcpenumsubnetelementsv5)
