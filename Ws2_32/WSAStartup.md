## WSAStartup

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int WSAStartup(
   ushort wVersionRequested,
   IntPtr lpWSAData
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-wsastartup)
