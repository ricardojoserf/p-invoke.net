## SHGetSpecialFolderLocation

```
[DllImport("shell32.dll")]
public static extern int SHGetSpecialFolderLocation(
   IntPtr hwnd,
   int nFolder,
   out IntPtr ppidl
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shgetspecialfolderlocation)
