## WNetGetConnection

```
[DllImport("Mpr.dll", SetLastError = true)]
public static extern uint WNetGetConnection(
   string lpLocalName,
   StringBuilder lpRemoteName,
   ref int lpnLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winnetwk/nf-winnetwk-wnetgetconnectiona)
