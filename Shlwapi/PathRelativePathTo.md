## PathRelativePathTo

```csharp
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern bool PathRelativePathTo(
   StringBuilder pszPath,
   [MarshalAs(UnmanagedType.LPWStr)] string pszFrom,
   DWORD dwAttrFrom,
   [MarshalAs(UnmanagedType.LPWStr)] string pszTo,
   DWORD dwAttrTo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathrelativepathtow)
