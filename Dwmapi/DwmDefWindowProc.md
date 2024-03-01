## DwmDefWindowProc

```
[DllImport("dwmapi.dll", SetLastError = true)]
public static extern IntPtr DwmDefWindowProc(
   IntPtr hwnd,
   uint msg,
   IntPtr wParam,
   IntPtr lParam,
   out IntPtr result
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/dwmapi/nf-dwmapi-dwmdefwindowproc)
