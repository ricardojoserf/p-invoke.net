## GetMenuString

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern int GetMenuString(
   IntPtr hMenu,
   uint uIDItem,
   StringBuilder lpString,
   int nMaxCount,
   uint uFlag
);
```

[Microsoft documentation](TODO)
