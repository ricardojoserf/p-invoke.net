## RealGetWindowClass

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern uint RealGetWindowClass(
   IntPtr hwnd,
   [Out] StringBuilder pszType,
   uint cchType
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-realgetwindowclassw)
