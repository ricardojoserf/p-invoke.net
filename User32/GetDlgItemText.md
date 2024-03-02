## GetDlgItemText

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern int GetDlgItemText(
   IntPtr hDlg,
   int nIDDlgItem,
   StringBuilder lpString,
   int cchMax
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getdlgitemtexta)
