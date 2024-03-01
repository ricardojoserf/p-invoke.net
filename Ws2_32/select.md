## select

```
[DllImport("ws2_32.dll", SetLastError = true)]
public static extern int select(
   int nfds,
   ref fd_set readfds,
   ref fd_set writefds,
   ref fd_set exceptfds,
   ref timeval timeout
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winsock/nf-winsock-select)
