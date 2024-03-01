## DwmSetColorizationParameters

```
[DllImport("dwmapi.dll", SetLastError = true)]
public static extern int DwmSetColorizationParameters(
   ref DWM_COLORIZATION_PARAMS parameters,
   [MarshalAs(UnmanagedType.Bool)] bool unknown
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/dwmapi/nf-dwmapi-dwmsetcolorizationparameters)
