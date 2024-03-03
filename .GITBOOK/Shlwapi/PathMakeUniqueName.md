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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-pathmakeuniquename)
