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

[Microsoft documentation](TODO)
