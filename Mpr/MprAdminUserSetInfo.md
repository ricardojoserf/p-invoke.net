## MprAdminUserSetInfo

```
[DllImport("Mpr.dll", SetLastError = true)]
public static extern uint MprAdminUserSetInfo(
   string servername,
   string username,
   uint level,
   IntPtr bufptr,
   out uint parm_err
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-mpradminusersetinfo)
