## SetWindowLongPtr

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr SetWindowLongPtr(
   IntPtr hWnd,
   int nIndex,
   IntPtr dwNewLong
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setwindowlongptrw)
