## DwmGetWindowAttribute

```
[DllImport("dwmapi.dll", SetLastError = true)]
public static extern int DwmGetWindowAttribute(
   IntPtr hwnd,
   int dwAttribute,
   IntPtr pvAttribute,
   int cbAttribute
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dwmapi/nf-dwmapi-dwmgetwindowattribute)
