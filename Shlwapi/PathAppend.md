## PathAppend

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern bool PathAppend(
   StringBuilder pszPath,
   [MarshalAs(
   UnmanagedType.LPWStr)] string pszMore
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathappendw)
