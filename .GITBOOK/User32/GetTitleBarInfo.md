## GetTitleBarInfo

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool GetTitleBarInfo(
   IntPtr hwnd,
   ref TITLEBARINFO pti
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-gettitlebarinfo)
