## ScreenToClient

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool ScreenToClient(
   IntPtr hWnd,
   ref POINT lpPoint
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-screentoclient)
