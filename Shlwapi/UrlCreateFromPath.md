## UrlCreateFromPath

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern int UrlCreateFromPath(
   [MarshalAs(UnmanagedType.LPWStr)] string pszPath,
   StringBuilder pszUrl,
   ref uint pcchUrl,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-urlcreatefrompathw)
