## keybd_event

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern void keybd_event(
   byte bVk,
   byte bScan,
   uint dwFlags,
   IntPtr dwExtraInfo
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-keybd_event)
