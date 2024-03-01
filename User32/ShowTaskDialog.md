## ShowTaskDialog

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int ShowTaskDialog(
   IntPtr hWndParent,
   IntPtr hInstance,
   string pszWindowTitle,
   string pszMainInstruction,
   string pszContent,
   int dwCommonButtons,
   IntPtr pszIcon,
   out int pnButton
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-showtaskdialog)
