## CreateWindowStation

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern IntPtr CreateWindowStationA(
   string lpwinsta,
   uint dwReserved,
   uint dwDesiredAccess,
   IntPtr lpsa
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-createwindowstationa)
