## SHQueryRecycleBin

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHQueryRecycleBin(
   string pszRootPath,
   ref SHQUERYRBINFO pSHQueryRBInfo
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shqueryrecyclebinw)
