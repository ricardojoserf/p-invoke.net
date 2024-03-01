## EnumDisplaySettingsEx

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern bool EnumDisplaySettingsExA(
   string lpszDeviceName,
   uint iModeNum,
   ref DEVMODE lpDevMode,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-enumdisplaysettingsexa)
