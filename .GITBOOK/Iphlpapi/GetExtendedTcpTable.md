## GetExtendedTcpTable

```
[DllImport("Iphlpapi.dll", SetLastError = true)]
public static extern uint GetExtendedTcpTable(
   IntPtr pTcpTable,
   ref int pdwSize,
   bool bOrder,
   uint ulAf,
   TCP_TABLE_CLASS TableClass,
   uint Reserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/iphlpapi/nf-iphlpapi-getextendedtcptable)
