## PathUnExpandEnvStrings

```csharp
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern bool PathUnExpandEnvStrings(
   [MarshalAs(UnmanagedType.LPWStr)] string pszPath,
   [MarshalAs(UnmanagedType.LPWStr)] StringBuilder pszBuf,
   uint cchBuf
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathunexpandenvstringsw)
