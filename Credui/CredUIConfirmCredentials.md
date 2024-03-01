## CredUIConfirmCredentials

```
[DllImport("Credui.dll", SetLastError = true)]
public static extern CREDUI_RETURN CredUIConfirmCredentials(
   string pszTargetName,
   [MarshalAs(
   UnmanagedType.Bool)] bool bConfirm
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/credui/nf-credui-creduiconfirmcredentials)
