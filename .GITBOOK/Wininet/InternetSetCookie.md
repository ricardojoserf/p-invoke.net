## InternetSetCookie

```csharp
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool InternetSetCookie(
   string lpszUrl,
   string lpszCookieName,
   string lpszCookieData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-internetsetcookiea)
