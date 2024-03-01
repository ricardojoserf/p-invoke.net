## SHPathPrepareForWrite

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern int SHPathPrepareForWrite(
   IntPtr hwnd,
   IntPtr pbc,
   string pszPath,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-shpathprepareforwrite)
