## CredUIParseUserName

```
[DllImport("Credui.dll", SetLastError = true)]
public static extern CREDUI_RETURN CredUIParseUserName(
   string pszUserName,
   StringBuilder pszUser,
   uint ulUserMaxChars,
   StringBuilder pszDomain,
   uint ulDomainMaxChars
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/wincred/nf-wincred-creduiparseusernamea)
