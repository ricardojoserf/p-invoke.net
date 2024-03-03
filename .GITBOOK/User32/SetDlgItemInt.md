## SetDlgItemInt

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool SetDlgItemInt(
   IntPtr hDlg,
   int nIDDlgItem,
   uint uValue,
   bool bSigned
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setdlgitemint)
