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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/dotnet/api/system.windows.forms.taskdialog.showdialog?view=windowsdesktop-8.0)
