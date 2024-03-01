## GetLayeredWindowAttributes

```
[DllImport("user32.dll")]
public static extern bool GetLayeredWindowAttributes(
   IntPtr hwnd,
   out uint crKey,
   out byte bAlpha,
   out uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getlayeredwindowattributes)
