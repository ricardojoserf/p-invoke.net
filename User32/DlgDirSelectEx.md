## DlgDirSelectEx

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern bool DlgDirSelectExA(IntPtr hwndDlg,
   StringBuilder lpString,
   int cchOut,
   int idListBox
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-dlgdirselectexa)
