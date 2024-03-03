## PathCompactPathEx

```csharp
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern bool PathCompactPathEx(
   StringBuilder pszOut,
   [MarshalAs(UnmanagedType.LPWStr)] string pszSrc,
   uint cchMax,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathcompactpathexw)
