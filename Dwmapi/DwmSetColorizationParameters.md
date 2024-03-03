## DwmSetColorizationParameters

```csharp
[DllImport("dwmapi.dll", SetLastError = true)]
public static extern int DwmSetColorizationParameters(
   ref DWM_COLORIZATION_PARAMS parameters,
   [MarshalAs(UnmanagedType.Bool)] bool unknown
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/dwmapi/nf-dwmapi-dwmgetcolorizationcolor)
