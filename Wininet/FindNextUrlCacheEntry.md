## FindNextUrlCacheEntry

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool FindNextUrlCacheEntry(
   IntPtr hFind,
   IntPtr lpNextCacheEntryInfo,
   ref uint lpdwNextCacheEntryInfoBufferSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-findnexturlcacheentrya)
