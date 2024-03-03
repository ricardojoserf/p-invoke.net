## PathIsRelative

```csharp
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern bool PathIsRelative(
   [MarshalAs(UnmanagedType.LPWStr)] string pszPath
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathisrelativew)
