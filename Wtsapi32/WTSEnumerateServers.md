## WTSEnumerateServers

```
[DllImport("wtsapi32.dll", SetLastError = true)]
public static extern bool WTSEnumerateServers(
   string pDomainName,
   int Reserved,
   int Version,
   ref IntPtr ppServerInfo,
   ref int pCount
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wtsapi32/nf-wtsapi32-wtsenumerateserversa)
