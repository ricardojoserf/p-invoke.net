## PathIsSameRoot

```
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern bool PathIsSameRoot(
   [MarshalAs(UnmanagedType.LPWStr)] string pszPath1,
   [MarshalAs(UnmanagedType.LPWStr)] string pszPath2
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathissamerootw)
