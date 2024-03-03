## send

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int send(
   IntPtr s,
   byte[] buf,
   int len,
   int flags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winsock2/nf-winsock2-send)
