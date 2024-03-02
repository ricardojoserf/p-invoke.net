## RecvFrom

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int RecvFrom(
   IntPtr s,
   byte[] buf,
   int len,
   int flags,
   ref sockaddr_in from,
   ref int fromlen
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-recvfrom)
