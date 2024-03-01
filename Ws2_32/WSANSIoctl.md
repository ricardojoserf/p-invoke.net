## WSANSIoctl

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int WSANSIoctl(
   IntPtr hLookup,
   uint dwControlCode,
   IntPtr lpvInBuffer,
   uint cbInBuffer,
   IntPtr lpvOutBuffer,
   uint cbOutBuffer,
   ref uint lpcbBytesReturned,
   IntPtr lpCompletion
);
```

[Microsoft documentation](TODO)
