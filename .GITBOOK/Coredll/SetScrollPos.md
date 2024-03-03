## SetScrollPos

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern int SetScrollPos(
   IntPtr hWnd,
   int nBar,
   int nPos,
   bool bRedraw
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setscrollpos)
