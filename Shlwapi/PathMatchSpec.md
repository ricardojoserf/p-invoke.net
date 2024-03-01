## PathMatchSpec

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern bool PathMatchSpec(
   [MarshalAs(UnmanagedType.LPWStr)] string pszFile,
   [MarshalAs(UnmanagedType.LPWStr)] string pszSpec
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathmatchspecw)
