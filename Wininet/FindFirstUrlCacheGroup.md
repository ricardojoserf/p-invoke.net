## FindFirstUrlCacheGroup

```csharp
[DllImport("wininet.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern IntPtr FindFirstUrlCacheGroup(
   uint dwFlags,
   uint dwFilter,
   IntPtr lpSearchCondition,
   uint dwSearchCondition,
   IntPtr lpGroupId,
   IntPtr lpReserved
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wininet/nf-wininet-findfirsturlcachegroup)
