## tcp_keepalive

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int tcp_keepalive(
   IntPtr s,
   byte[] inBuf,
   uint inLen,
   byte[] outBuf,
   uint outLen,
   ref uint bytesRet
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/winsock/tcp-keepalive)
