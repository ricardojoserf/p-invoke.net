## GetWindowPlacement

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool GetWindowPlacement(
   IntPtr hWnd,
   ref WINDOWPLACEMENT lpwndpl
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getwindowplacement)
