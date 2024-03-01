## EnumChildWindows

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumChildWindows(
   IntPtr hWndParent,
   EnumWindowsProc lpEnumFunc,
   IntPtr lParam
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-enumchildwindows)
