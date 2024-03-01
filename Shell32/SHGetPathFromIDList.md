## SHGetPathFromIDList

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern bool SHGetPathFromIDList(
   IntPtr pidl,
   StringBuilder pszPath
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shgetpathfromidlistw)
