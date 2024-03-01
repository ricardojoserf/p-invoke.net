## FindFirstUrlCacheEntry

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern IntPtr FindFirstUrlCacheEntry(
   string lpszUrlSearchPattern,
   IntPtr lpFirstCacheEntryInfo,
   ref uint lpdwFirstCacheEntryInfoBufferSize
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-findfirsturlcacheentrya)
