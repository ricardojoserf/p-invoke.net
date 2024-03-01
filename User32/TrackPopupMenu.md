## TrackPopupMenu

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool TrackPopupMenu(
   IntPtr hMenu,
   uint uFlags,
   int x,
   int y,
   int nReserved,
   IntPtr hWnd,
   IntPtr prcRect
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-trackpopupmenu)
