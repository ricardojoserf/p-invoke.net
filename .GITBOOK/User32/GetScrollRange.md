## GetScrollRange

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool GetScrollRange(
   IntPtr hWnd,
   int nBar,
   out int lpMinPos,
   out int lpMaxPos
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getscrollrange)
