## ChangeDisplaySettingsEx

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int ChangeDisplaySettingsEx(
   string lpszDeviceName,
   ref DEVMODE lpDevMode,
   IntPtr hwnd,
   uint dwflags,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-changedisplaysettingsexa)
