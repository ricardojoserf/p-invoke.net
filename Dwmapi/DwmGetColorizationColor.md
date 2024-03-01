## DwmGetColorizationColor

```
[DllImport("dwmapi.dll", SetLastError = true)]
public static extern int DwmGetColorizationColor(
   out uint pcrColorization,
   [MarshalAs(
   UnmanagedType.Bool)] out bool pfOpaqueBlend
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/dwmapi/nf-dwmapi-dwmgetcolorizationcolor)
