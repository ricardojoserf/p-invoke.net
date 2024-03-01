## SetWindowLong

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int SetWindowLong(
   IntPtr hWnd,
   int nIndex,
   int dwNewLong
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setwindowlongw)
