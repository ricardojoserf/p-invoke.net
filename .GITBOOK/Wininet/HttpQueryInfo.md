## HttpQueryInfo

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool HttpQueryInfo(
   IntPtr hRequest,
   uint dwInfoLevel,
   IntPtr lpBuffer,
   ref uint lpdwBufferLength,
   ref uint lpdwIndex
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-httpqueryinfoa)
