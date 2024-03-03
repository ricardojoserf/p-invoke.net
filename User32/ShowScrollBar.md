## ShowScrollBar

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool ShowScrollBar(
   IntPtr hWnd,
   int wBar,
   bool bShow
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-showscrollbar)
