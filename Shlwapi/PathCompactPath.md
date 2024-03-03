## PathCompactPath

```csharp
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern bool PathCompactPath(
   IntPtr hDC,
   StringBuilder pszPath,
   uint dx
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathcompactpathexw)
