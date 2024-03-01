## SHGetFolderLocation

```
[DllImport("shell32.dll")]
public static extern int SHGetFolderLocation(
   IntPtr hwnd,
   int nFolder,
   IntPtr hToken,
   uint dwReserved,
   out IntPtr ppidl
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shgetfolderlocation)
