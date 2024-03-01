## ScrollWindow

```
[DllImport("user32.dll", SetLastError = true)]
public static extern int ScrollWindow(
   IntPtr hWnd,
   int nXAmount,
   int nYAmount,
   ref RECT lpRect,
   ref RECT lpClipRect
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-scrollwindow)
