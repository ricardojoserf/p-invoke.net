## InternetGetCookieEx

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool InternetGetCookieEx(
   string lpszUrl,
   string lpszCookieName,
   StringBuilder lpszCookieData,
   ref uint lpdwSize,
   uint dwFlags,
   IntPtr lpReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-internetgetcookieexa)
