## PrintWindow

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool PrintWindow(
   IntPtr hwnd,
   IntPtr hdcBlt,
   uint nFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-printwindow)
