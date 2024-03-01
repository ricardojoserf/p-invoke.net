## SystemParametersInfo

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool SystemParametersInfo(
   uint uiAction,
   uint uiParam,
   ref RECT pvParam,
   uint fWinIni
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-systemparametersinfoa)
