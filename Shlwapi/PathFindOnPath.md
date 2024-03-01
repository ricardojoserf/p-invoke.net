## PathFindOnPath

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern bool PathFindOnPath(
   StringBuilder pszFile,
   [MarshalAs(UnmanagedType.LPArray,
   ArraySubType = UnmanagedType.LPWStr)] string[] ppszOtherDirs
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathfindonpathw)
