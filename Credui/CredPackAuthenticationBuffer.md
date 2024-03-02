## CredPackAuthenticationBuffer

```
[DllImport("Credui.dll", SetLastError = true)]
public static extern CREDUI_RETURN CredPackAuthenticationBuffer(
   CREDUI_INFO pUiInfo,
   [MarshalAs(UnmanagedType.LPStr)] string pszUserName,
   [MarshalAs(UnmanagedType.LPStr)] string pszPassword,
   IntPtr pPackedCredentials,
   ref uint pcPackedCredentials
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credpackauthenticationbuffera)
