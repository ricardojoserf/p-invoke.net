## listen

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int listen(
   IntPtr s,
   int backlog
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winsock2/nf-winsock2-listen)
