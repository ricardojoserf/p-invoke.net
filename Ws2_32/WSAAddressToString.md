## WSAAddressToString

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int WSAAddressToString(
   IntPtr lpsaAddress,
   uint dwAddressLength,
   IntPtr lpProtocolInfo,
   StringBuilder lpszAddressString,
   ref uint lpdwAddressStringLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/ws2tcpip/nf-ws2tcpip-wsaaddresstostring)
