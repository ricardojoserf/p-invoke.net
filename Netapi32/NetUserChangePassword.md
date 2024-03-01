## NetUserChangePassword

```
[DllImport("netapi32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static extern uint NetUserChangePassword(
   string DomainName,
   string UserName,
   string OldPassword,
   string NewPassword
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-netuserchangepassword)
