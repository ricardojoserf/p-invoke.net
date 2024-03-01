## WSAStringToAddress

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int WSAStringToAddress(
   string AddressString,
   int AddressFamily,
   IntPtr lpProtocolInfo,
   ref sockaddr_in lpAddress,
   ref int lp
```

Microsoft documentation: (TODO)
