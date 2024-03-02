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

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/mprapi/nf-mprapi-mpradminusergetinfo)
