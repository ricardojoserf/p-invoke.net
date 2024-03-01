## inet_pton

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int inet_pton(
   int Family,
   string pStringBuf,
   IntPtr pAddrBuf
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ws2tcpip/nf-ws2tcpip-inet_pton)
