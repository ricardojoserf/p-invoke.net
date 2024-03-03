## SetWindowPlacement

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool SetWindowPlacement(
   IntPtr hWnd,
   [In] ref WINDOWPLACEMENT lpwndpl
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setwindowplacement)
