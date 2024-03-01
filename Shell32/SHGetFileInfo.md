## SHGetFileInfo

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern IntPtr SHGetFileInfo(
   string pszPath,
   uint dwFileAttributes,
   ref SHFILEINFO psfi,
   uint cbSizeFileInfo,
   uint uFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shgetfileinfow)
