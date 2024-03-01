## ImpersonateDdeClientWindow

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool ImpersonateDdeClientWindow(
   IntPtr hWndClient,
   IntPtr hWndServer,
   out uint pid
);
```

[Microsoft documentation](TODO)
