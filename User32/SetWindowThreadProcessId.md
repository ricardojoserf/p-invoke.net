## SetWindowThreadProcessId

```
[DllImport("user32.dll", SetLastError = true)]
public static extern uint SetWindowThreadProcessId(
   IntPtr hWnd,
   ref uint lpdwProcessId
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setwindowthreadprocessid)
