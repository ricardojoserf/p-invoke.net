## GetIpNetTable

```csharp
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern uint GetIpNetTable(
   IntPtr pIpNetTable,
   ref uint pdwSize,
   bool bOrder
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-getipnettable)
