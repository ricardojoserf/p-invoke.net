## KillTimer

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool KillTimer(
   IntPtr hWnd,
   uint uIDEvent
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-killtimer)
