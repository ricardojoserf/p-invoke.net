## FindNextUrlCacheGroup

```
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool FindNextUrlCacheGroup(
   IntPtr hFind,
   IntPtr lpNextCacheGroupInfo,
   ref uint lpdwNextCacheGroupInfoBufferSize
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-findnexturlcachegroup)
