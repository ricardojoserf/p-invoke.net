## SHGetNameFromIDList

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHGetNameFromIDList(
   IntPtr pidl,
   uint sigdnName,
   out IntPtr ppszName
);
```

[Microsoft documentation](TODO)
