## InvalidateRgn

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool InvalidateRgn(
   IntPtr hWnd,
   IntPtr hRgn,
   bool bErase
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-invalidatergn)
