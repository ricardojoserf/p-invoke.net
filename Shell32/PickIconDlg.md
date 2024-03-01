## PickIconDlg

```
[DllImport("shell32.dll", CharSet = CharSet.Unicode)]
public static extern int PickIconDlg(
   IntPtr hwndOwner,
   StringBuilder pszIconPath,
   uint cchIconPath,
   out int piIconIndex
);
```

Microsoft documentation: (TODO)
