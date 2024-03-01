## ImpersonateDdeClientWindow

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool ImpersonateDdeClientWindow(
   IntPtr hWndClient,
   IntPtr hWndServer,
   out uint pid
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-impersonateddeclientwindow)
