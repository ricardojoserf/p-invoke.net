## DwmExtendFrameIntoClientArea

```
[DllImport("dwmapi.dll", SetLastError = true)]
public static extern int DwmExtendFrameIntoClientArea(
   IntPtr hwnd,
   ref MARGINS pMarInset
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/dwmapi/nf-dwmapi-dwmextendframeintoclientarea)
