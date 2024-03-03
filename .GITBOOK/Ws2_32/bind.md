## bind

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int bind(
   IntPtr s,
   ref sockaddr_in name,
   int namelen
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-bind)
