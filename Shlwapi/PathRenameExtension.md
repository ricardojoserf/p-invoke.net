## PathRenameExtension

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern bool PathRenameExtension(
   StringBuilder pszPath,
   [MarshalAs(UnmanagedType.LPWStr)] string pszExt
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathrenameextensionw)
