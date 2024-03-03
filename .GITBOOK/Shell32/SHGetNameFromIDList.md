## SHGetNameFromIDList

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHGetNameFromIDList(
   IntPtr pidl,
   uint sigdnName,
   out IntPtr ppszName
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/shobjidl_core/nf-shobjidl_core-shgetnamefromidlist)
