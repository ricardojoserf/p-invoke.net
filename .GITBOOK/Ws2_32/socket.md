## socket

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern IntPtr socket(
   int af,
   int type,
   int protocol
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winsock2/nf-winsock2-socket)
