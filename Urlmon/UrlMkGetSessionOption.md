## UrlMkGetSessionOption

```
[DllImport("urlmon.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern int UrlMkGetSessionOption(
   int dwOption,
   IntPtr pBuffer,
   int dwBufferLength,
   ref int pdwBufferLength,
   int dwReserved
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/urlmon/nf-urlmon-urlmkgetsessionoption)
