## ClientRectangle

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool GetClientRect(
   IntPtr hWnd,
   [In,
   Out] ref RECT lpRect
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getclientrect)
