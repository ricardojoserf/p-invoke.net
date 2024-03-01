## PathMakeUniqueName

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern void PathMakeUniqueName(
   StringBuilder pszUniqueName,
   uint cchMax,
   string pszTemplate,
   string pszLongPlate,
   string pszDir
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathmakeuniquename)
