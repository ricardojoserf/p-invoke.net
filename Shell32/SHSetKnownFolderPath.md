## SHSetKnownFolderPath

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHSetKnownFolderPath(
   ref Guid rfid,
   uint dwFlags,
   IntPtr hToken,
   string pszPath
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shsetknownfolderpath)
