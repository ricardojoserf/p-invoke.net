## HttpOpenRequest

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern IntPtr HttpOpenRequest(
   IntPtr hConnect,
   string lpszVerb,
   string lpszObjectName,
   string lpszVersion,
   string lpszReferrer,
   string lpszAcceptTypes,
   uint dwFlags,
   IntPtr dwContext
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-httpopenrequesta)
