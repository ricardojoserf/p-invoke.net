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

[Microsoft documentation](TODO)
