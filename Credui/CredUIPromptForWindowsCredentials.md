## CredUIPromptForWindowsCredentials

```
[DllImport("Credui.dll", SetLastError = true)]
public static extern CREDUI_RETURN CredUIPromptForWindowsCredentials(
   ref CREDUI_INFO pUiInfo,
   uint dwAuthError,
   ref uint pulAuthPackage,
   IntPtr pvInAuthBuffer,
   uint ulInAuthBufferSize,
   out IntPtr ppvOutAuthBuffer,
   out uint pulOutAuthBufferSize,
   [MarshalAs(
   UnmanagedType.Bool)] ref bool pfSave,
   CREDUIWIN dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/credui/nf-credui-creduipromptforwindowscredentialsa)
