## GetWindowInfo

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool GetWindowInfo(
   IntPtr hwnd,
   ref WINDOWINFO pwi
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getwindowinfo)
