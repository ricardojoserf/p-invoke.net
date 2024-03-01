## MprAdminUserGetInfo

```
[DllImport("Mpr.dll", SetLastError = true)]
public static extern uint MprAdminUserGetInfo(
   string servername,
   string username,
   uint level,
   out IntPtr bufptr
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/lmaccess/nf-lmaccess-mpradminusergetinfo)
