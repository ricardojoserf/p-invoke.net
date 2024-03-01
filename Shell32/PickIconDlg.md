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

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/shellapi/nf-shellapi-pickicondlg)
