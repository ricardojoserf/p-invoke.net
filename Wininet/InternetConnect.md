## InternetConnect

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern IntPtr InternetConnect(
   IntPtr hInternet,
   string lpszServerName,
   ushort nServerPort,
   string lpszUsername,
   string lpszPassword,
   uint dwService,
   uint dwFlags,
   IntPtr dwContext
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-internetconnecta)
