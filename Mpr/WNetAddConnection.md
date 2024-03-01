## WNetAddConnection

```
[DllImport("Mpr.dll", SetLastError = true)]
public static extern uint WNetAddConnection(
   string lpszRemoteName,
   string lpszPassword,
   string lpszLocalName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnetwk/nf-winnetwk-wnetaddconnectiona)
