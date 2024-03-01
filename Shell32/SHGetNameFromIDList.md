## SHGetNameFromIDList

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHGetNameFromIDList(
   IntPtr pidl,
   uint sigdnName,
   out IntPtr ppszName
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shgetnamefromidlistw)
