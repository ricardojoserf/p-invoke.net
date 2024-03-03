## WSANSIoctl

```csharp
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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winsock2/nf-winsock2-wsaioctl)
