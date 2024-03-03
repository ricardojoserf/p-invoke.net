## SetScrollRange

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool SetScrollRange(
   IntPtr hWnd,
   int nBar,
   int nMinPos,
   int nMaxPos,
   bool bRedraw
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setscrollrange)
