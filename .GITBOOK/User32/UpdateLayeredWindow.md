## UpdateLayeredWindow

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool UpdateLayeredWindow(
   IntPtr hWnd,
   IntPtr hdcDst,
   ref POINT pptDst,
   ref SIZE psize,
   IntPtr hdcSrc,
   ref POINT pptSrc,
   int crKey,
   ref BLENDFUNCTION pblend,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-updatelayeredwindow)
