## ExitWindowsEx

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool ExitWindowsEx(
   uint uFlags,
   uint dwReason
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-exitwindowsex)
