## InternetGetCookie

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool InternetGetCookie(
   string lpszUrl,
   string lpszCookieName,
   StringBuilder lpszCookieData,
   ref uint lpdwSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-internetgetcookiea)
