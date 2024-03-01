## HttpSendRequest

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool HttpSendRequest(
   IntPtr hRequest,
   string lpszHeaders,
   uint dwHeadersLength,
   IntPtr lpOptional,
   uint dwOptionalLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-httpsendrequesta)
