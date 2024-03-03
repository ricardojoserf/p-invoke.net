## PathCommonPrefix

```csharp
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern int PathCommonPrefix(
   [MarshalAs(UnmanagedType.LPWStr)] string pszFile1,
   [MarshalAs(UnmanagedType.LPWStr)] string pszFile2,
   StringBuilder pszPath
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathcommonprefixw)
