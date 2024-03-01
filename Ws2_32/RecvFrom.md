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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/winsock/recvfrom)
