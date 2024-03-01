## WSALookupServiceNext

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int WSALookupServiceNext(
   IntPtr hLookup,
   uint dwControlFlags,
   ref uint lpdwBufferLength,
   IntPtr lpqsResults
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-wsalookupservicenexta)
