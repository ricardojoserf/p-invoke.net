## IsDialogMessage

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool IsDialogMessage(
   IntPtr hDlg,
   ref MSG lpMsg
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-isdialogmessagew)
