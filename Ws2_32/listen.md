## listen

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int listen(
   IntPtr s,
   int backlog
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-listen)
