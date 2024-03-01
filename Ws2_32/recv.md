## recv

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int recv(
   IntPtr s,
   byte[] buf,
   int len,
   int flags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-recv)
