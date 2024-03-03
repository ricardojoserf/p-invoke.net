## DhcpGetVersion

```csharp
[DllImport("dhcpsapi.dll", SetLastError = true)]
public static extern uint DhcpGetVersion(
   IntPtr ServerIpAddress,
   out uint MajorVersion,
   out uint MinorVersion
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/dhcpsapi/nf-dhcpsapi-dhcpgetversion)
