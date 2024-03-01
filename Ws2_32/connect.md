## connect

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int connect(
   IntPtr s,
   ref sockaddr_in name,
   int namelen
);
```

Microsoft documentation: (TODO)
