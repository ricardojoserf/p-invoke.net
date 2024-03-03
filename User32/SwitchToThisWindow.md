## SwitchToThisWindow

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern void SwitchToThisWindow(
   IntPtr hWnd,
   bool fAltTab
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-switchtothiswindow)
