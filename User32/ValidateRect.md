## ValidateRect

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool ValidateRect(
   IntPtr hWnd,
   [In] ref RECT lpRect
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-validaterect)
