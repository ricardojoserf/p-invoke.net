## SetLayeredWindowAttributes

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool SetLayeredWindowAttributes(
   IntPtr hwnd,
   uint crKey,
   byte bAlpha,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setlayeredwindowattributes)
