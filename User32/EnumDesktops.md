## EnumDesktops

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern bool EnumDesktopsA(
   IntPtr hwinsta,
   EnumDesktopProc lpEnumFunc,
   IntPtr lParam
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-enumdesktopsa)
