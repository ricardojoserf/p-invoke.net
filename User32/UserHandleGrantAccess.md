## UserHandleGrantAccess

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool UserHandleGrantAccess(
   IntPtr hUserHandle,
   IntPtr hJob,
   bool bGrant
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-userhandlegrantaccess)
