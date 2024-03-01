## GetMouseMovePointsEx

```
[DllImport("user32.dll")]
public static extern int GetMouseMovePointsEx(
   uint cbSize,
   [In,
   Out] ref MOUSEMOVEPOINT lppt,
   [In,
   Out] MOUSEMOVEPOINT[] lpptBuf,
   int nBufPoints,
   uint resolution
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getmousemovepointsex)
