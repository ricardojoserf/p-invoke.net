## GetIpAddrTable

```csharp
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern uint GetIpAddrTable(
   IntPtr pIpAddrTable,
   ref uint pdwSize,
   bool bOrder
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-getipaddrtable)
