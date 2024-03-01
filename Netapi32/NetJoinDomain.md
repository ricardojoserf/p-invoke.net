## NetJoinDomain

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetJoinDomain(
   string lpServer,
   string lpDomain,
   string lpAccountOU,
   string lpAccount,
   string lpPassword,
   JoinOptions fJoinOptions
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmapibuf/nf-lmapibuf-netjoindomain)
