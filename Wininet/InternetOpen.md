## InternetOpen

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern IntPtr InternetOpen(
   string lpszAgent,
   uint dwAccessType,
   string lpszProxy,
   string lpszProxyBypass,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-internetopena)
