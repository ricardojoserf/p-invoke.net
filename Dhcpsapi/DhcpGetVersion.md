## DhcpGetVersion

```
[DllImport("dhcpsapi.dll", SetLastError = true)]
public static extern uint DhcpGetVersion(
   IntPtr ServerIpAddress,
   out uint MajorVersion,
   out uint MinorVersion
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/dhcpssdk/nf-dhcpssdk-dhcpgetversion)
