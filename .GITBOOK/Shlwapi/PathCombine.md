## PathCombine

```csharp
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern IntPtr PathCombine(
   StringBuilder pszDest,
   [MarshalAs(UnmanagedType.LPWStr)] string pszDir,
   [MarshalAs(UnmanagedType.LPWStr)] string pszFile
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-pathcombinew)
