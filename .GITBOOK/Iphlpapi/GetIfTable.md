## GetIfTable

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern uint GetIfTable(
   IntPtr pIfTable,
   ref uint pdwSize,
   bool bOrder
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-getiftable)
