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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winsock2/nf-winsock2-wsaaddresstostringa)
