## SHGetDiskFreeSpace

```
[DllImport("kernel32.dll", CharSet = CharSet.Unicode)]
public static extern bool SHGetDiskFreeSpace(
   string pszVolume,
   out ulong pqwFreeCaller,
   out ulong pqwTotal,
   out ulong pqwFree
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-shgetdiskfreespaceexw)
