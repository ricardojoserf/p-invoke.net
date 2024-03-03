## DwmGetCompositionTimingInfo

```
[DllImport("dwmapi.dll", SetLastError = true)]
public static extern int DwmGetCompositionTimingInfo(
   IntPtr hwnd,
   ref DWM_TIMING_INFO pTimingInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dwmapi/nf-dwmapi-dwmgetcompositiontiminginfo)
