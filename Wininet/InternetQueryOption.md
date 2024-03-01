## InternetQueryOption

```
[DllImport("wininet.dll", SetLastError = true)]
public static extern bool InternetQueryOption(
   IntPtr hInternet,
   uint dwOption,
   ref INTERNET_PER_CONN_OPTION_LIST lpOptionList,
   ref uint lpdwBufferLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-internetqueryoptiona)
