## MoveWindow

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool MoveWindow(
   IntPtr hWnd,
   int X,
   int Y,
   int nWidth,
   int nHeight,
   bool bRepaint
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-movewindow)
