## SHGetKnownFolderPath

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHGetKnownFolderPath(
   ref Guid rfid,
   uint dwFlags,
   IntPtr hToken,
   out IntPtr pszPath
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shgetknownfolderpath)
