## CredUnPackAuthenticationBuffer

```
[DllImport("Credui.dll", SetLastError = true)]
public static extern CREDUI_RETURN CredUnPackAuthenticationBuffer(
   CREDUI_INFO pUiInfo,
   IntPtr pAuthBuffer,
   uint cbAuthBuffer,
   StringBuilder pszUserName,
   uint ulUserMaxChars,
   StringBuilder pszDomainName,
   uint ulDomainMaxChars,
   StringBuilder pszPassword,
   uint ulPasswordMaxChars
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-credunpackauthenticationbuffera)
