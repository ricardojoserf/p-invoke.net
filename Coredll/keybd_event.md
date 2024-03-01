## keybd_event

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern void keybd_event(
   byte bVk,
   byte bScan,
   int dwFlags,
   int dwExtraInfo
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-keybd_event)
