## setsockopt

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int setsockopt(
   IntPtr s,
   int level,
   int optname,
   byte[] optval,
   int optlen
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-setsockopt)
