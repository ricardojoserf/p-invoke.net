## DnsQueryEx

```
[DllImport("dnsapi.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int DnsQueryEx(
   ref DNS_QUERY_REQUEST pQueryRequest,
   ref DNS_QUERY_RESULT pQueryResults,
   IntPtr pQueryCancel
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/windns/nf-windns-dnsqueryex)
