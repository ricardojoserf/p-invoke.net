## InternetGetLastResponseInfo

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool InternetGetLastResponseInfo(
   out uint lpdwError,
   StringBuilder lpszBuffer,
   ref uint lpdwBufferLength
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-internetgetlastresponseinfoa)
