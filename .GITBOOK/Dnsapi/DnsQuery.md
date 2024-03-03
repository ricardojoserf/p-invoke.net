## DnsQuery

```csharp
[DllImport("dnsapi.dll", EntryPoint = "DnsQuery_A", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern int DnsQuery(
   string lpstrName,
   QueryTypes wType,
   QueryOptions options,
   IntPtr pExtra,
   ref IntPtr ppQueryResults,
   IntPtr pReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/windns/nf-windns-dnsquery_a)
