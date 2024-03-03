## EnumDisplaySettings

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern bool EnumDisplaySettingsA(string lpszDeviceName,
   uint iModeNum,
   ref DEVMODE lpDevMode
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-enumdisplaysettingsa)
