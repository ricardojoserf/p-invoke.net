## AddIPAddress

```csharp
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern int AddIPAddress(
   uint Address,
   uint IpMask,
   int IfIndex,
   out MIB_IPINTERFACE_ROW Row
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-addipaddress)
