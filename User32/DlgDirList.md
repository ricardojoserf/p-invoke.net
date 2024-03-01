## DlgDirList

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern int DlgDirListA(
   IntPtr hDlg,
   [MarshalAs(
   UnmanagedType.LPStr)] StringBuilder lpPathSpec,
   int nIDListBox,
   int nIDStaticPath,
   uint uFileType
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-dlgdirlista)
