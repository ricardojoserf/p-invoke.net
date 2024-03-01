## GetDlgItemInt

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool GetDlgItemInt(
   IntPtr hDlg,
   int nIDDlgItem,
   ref bool lpTranslated,
   bool bSigned
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getdlgitemint)
