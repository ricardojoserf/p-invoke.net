## TaskDialog

```
[DllImport("Comctl32.dll", SetLastError = true)]
public static extern int TaskDialog(
   IntPtr hwndOwner,
   IntPtr hInstance,
   [MarshalAs(UnmanagedType.LPWStr)] string pszWindowTitle,
   [MarshalAs(UnmanagedType.LPWStr)] string pszMainInstruction,
   [MarshalAs(UnmanagedType.LPWStr)] string pszContent,
   int dwCommonButtons,
   IntPtr pszIcon,
   out int pnButton
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/commctrl/nf-commctrl-taskdialog)
