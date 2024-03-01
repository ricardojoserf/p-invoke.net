## CharPrevEx

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern IntPtr CharPrevEx(
   uint codePage,
   IntPtr lpStart,
   IntPtr lpCurrent,
   uint flags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-charprevexw)
