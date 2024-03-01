## SHGetNewLinkInfo

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int SHGetNewLinkInfo(
   string pszLinkTo,
   string pszDir,
   StringBuilder pszName,
   out bool pfMustCopy,
   uint uFlags
);
```

[Microsoft documentation](TODO)
