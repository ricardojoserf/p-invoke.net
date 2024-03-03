## CredUIPromptForCredentialsW

```csharp
[DllImport("Credui.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern CREDUI_RETURN CredUIPromptForCredentialsW(
   ref CREDUI_INFO pUiInfo,
   [MarshalAs(UnmanagedType.LPWStr)] string pszTargetName,
   IntPtr Reserved,
   uint dwAuthError,
   StringBuilder pszUserName,
   uint ulUserNameMaxChars,
   StringBuilder pszPassword,
   uint ulPasswordMaxChars,
   [MarshalAs(UnmanagedType.Bool)] ref bool pfSave,
   CREDUI_FLAGS dwFlags
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-creduipromptforcredentialsw)
