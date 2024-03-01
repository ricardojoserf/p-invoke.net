## EnumDisplayDevices

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern bool EnumDisplayDevicesA(string lpDevice,
   uint iDevNum,
   ref DISPLAY_DEVICE lpDisplayDevice,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-enumdisplaydevicesa)
