## SHGetDataFromIDList

```csharp
[DllImport("shell32.dll")]
public static extern int SHGetDataFromIDList(
   IntPtr psf,
   IntPtr pidl,
   uint nFormat,
   ref IntPtr pv,
   uint cb
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/shlobj_core/nf-shlobj_core-shgetdatafromidlistw)
