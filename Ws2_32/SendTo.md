## SendTo

```csharp
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int SendTo(
   IntPtr s,
   byte[] buf,
   int len,
   int flags,
   ref sockaddr_in to,
   int tolen
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-sendto)
