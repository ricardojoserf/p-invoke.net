## accept

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern IntPtr accept(
   IntPtr s,
   IntPtr addr,
   IntPtr addrlen
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winsock2/nf-winsock2-accept)
