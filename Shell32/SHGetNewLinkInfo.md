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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-shgetnewlinkinfoa)
