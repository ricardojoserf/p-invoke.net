## InetNtop

```csharp
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern IntPtr InetNtop(
   int Family,
   IntPtr pAddr,
   IntPtr pStringBuf,
   int StringBufSize
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/ws2tcpip/nf-ws2tcpip-inetntopw)
