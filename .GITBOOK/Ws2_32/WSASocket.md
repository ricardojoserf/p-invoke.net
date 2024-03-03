## WSASocket

```csharp
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern IntPtr WSASocket(
   int af,
   int type,
   int protocol,
   IntPtr lpProtocolInfo,
   uint g,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winsock2/nf-winsock2-wsasocketa)
