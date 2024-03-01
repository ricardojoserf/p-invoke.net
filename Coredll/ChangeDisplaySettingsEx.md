## ChangeDisplaySettingsEx

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern int ChangeDisplaySettingsEx(
   string lpszDeviceName,
   ref DEVMODE lpDevMode,
   IntPtr hwnd,
   ChangeDisplaySettingsFlags dwflags,
   IntPtr lParam
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-changedisplaysettingsexa)
