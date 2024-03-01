## WSASocket

```
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

Microsoft documentation: (TODO)
