## SHGetFolderPath

```csharp
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHGetFolderPath(
   IntPtr hwndOwner,
   int nFolder,
   IntPtr hToken,
   uint dwFlags,
   StringBuilder lpszPath
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shgetfolderpathw)
