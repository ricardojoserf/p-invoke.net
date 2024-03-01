## GetScrollInfo

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool GetScrollInfo(
   IntPtr hwnd,
   int nBar,
   ref SCROLLINFO lpsi
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getscrollinfo)
