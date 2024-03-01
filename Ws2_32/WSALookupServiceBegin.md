## WSALookupServiceBegin

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int WSALookupServiceBegin(
   IntPtr qsRestrictions,
   uint dwControlFlags,
   ref IntPtr lphLookup
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-wsalookupservicebegina)
