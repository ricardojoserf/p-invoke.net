## SetDlgItemText

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetDlgItemText(
   IntPtr hDlg,
   int nIDDlgItem,
   string lpString
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setdlgitemtextw)
