## MonitorFromWindow

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr MonitorFromWindow(
   IntPtr hwnd,
   uint dwFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-monitorfromwindow)
