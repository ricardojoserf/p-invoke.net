## DwmEnableBlurBehindWindow

```csharp
[DllImport("dwmapi.dll", SetLastError = true)]
public static extern int DwmEnableBlurBehindWindow(
   IntPtr hwnd,
   ref DWM_BLURBEHIND pBlurBehind
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dwmapi/nf-dwmapi-dwmenableblurbehindwindow)
