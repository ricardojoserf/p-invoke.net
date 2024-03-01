## DlgDirListComboBox

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern int DlgDirListComboBoxA(IntPtr hDlg,
   [MarshalAs(UnmanagedType.LPStr)] StringBuilder lpPathSpec,
   int nIDComboBox,
   int nIDStaticPath,
   uint uFiletype
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-dlgdirlistcomboboxa)
