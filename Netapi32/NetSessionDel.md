## NetSessionDel

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetSessionDel(
   string ServerName,
   string UncClientName,
   string UserName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmshare/nf-lmshare-netsessiondel)
