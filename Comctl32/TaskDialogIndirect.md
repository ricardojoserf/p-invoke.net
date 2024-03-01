## TaskDialogIndirect

```
[DllImport("Comctl32.dll", SetLastError = true)]
public static extern int TaskDialogIndirect(
   [In] ref TASKDIALOGCONFIG pTaskConfig,
   out int pnButton,
   out int pnRadioButton,
   [MarshalAs(
   UnmanagedType.Bool)] out bool pfVerificationFlagChecked
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/commctrl/nf-commctrl-taskdialogindirect)
