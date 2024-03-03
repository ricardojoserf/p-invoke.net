## PathCreateFromUrl

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern int PathCreateFromUrl(
   [MarshalAs(UnmanagedType.LPWStr)] string pszUrl,
   StringBuilder pszPath,
   ref uint pcchPath,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathcreatefromurlw)
