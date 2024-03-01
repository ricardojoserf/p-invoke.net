## ChangeDisplaySettings

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern int ChangeDisplaySettings(
   [In] ref DEVMODE lpDevMode,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-changedisplaysettingsw)
