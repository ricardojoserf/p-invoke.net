## BeginPaint

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr BeginPaint(
   IntPtr hWnd,
   [In,
   Out] ref PAINTSTRUCT lpPaint
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-beginpaint)
