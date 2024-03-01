## InvalidateRect

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool InvalidateRect(
   IntPtr hWnd,
   IntPtr lpRect,
   bool bErase
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-invalidaterect)
