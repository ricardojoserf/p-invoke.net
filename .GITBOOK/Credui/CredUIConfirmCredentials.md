## CredUIConfirmCredentials

```csharp
[DllImport("Credui.dll", SetLastError = true)]
public static extern CREDUI_RETURN CredUIConfirmCredentials(
   string pszTargetName,
   [MarshalAs(UnmanagedType.Bool)] bool bConfirm
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-creduiconfirmcredentialsa)
