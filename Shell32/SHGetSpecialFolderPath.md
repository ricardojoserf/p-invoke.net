## SHGetSpecialFolderPath

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern bool SHGetSpecialFolderPath(
   IntPtr hwndOwner,
   StringBuilder lpszPath,
   int nFolder,
   bool fCreate
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shgetspecialfolderpathw)
