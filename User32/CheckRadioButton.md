## CheckRadioButton

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CheckRadioButton(
   IntPtr hDlg,
   int nIDFirstButton,
   int nIDLastButton,
   int nIDCheckButton
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-checkradiobutton)
