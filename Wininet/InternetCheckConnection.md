## InternetCheckConnection

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool InternetCheckConnection(
   string lpszUrl,
   uint dwFlags,
   uint dwReserved
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-internetcheckconnectiona)
