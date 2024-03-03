## SHPathPrepareForWrite

```csharp
[DllImport("shlwapi.dll", CharSet = CharSet.Unicode)]
public static extern int SHPathPrepareForWrite(
   IntPtr hwnd,
   IntPtr pbc,
   string pszPath,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shpathprepareforwritea)
