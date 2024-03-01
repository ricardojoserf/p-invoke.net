## DeferWindowPos

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DeferWindowPos(
   IntPtr hWinPosInfo,
   IntPtr hWnd,
   IntPtr hWndInsertAfter,
   int x,
   int y,
   int cx,
   int cy,
   uint uFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-deferwindowpos)
