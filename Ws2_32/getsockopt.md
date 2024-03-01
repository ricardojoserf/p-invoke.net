## getsockopt

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int getsockopt(
   IntPtr s,
   int level,
   int optname,
   byte[] optval,
   ref int optlen
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-getsockopt)
