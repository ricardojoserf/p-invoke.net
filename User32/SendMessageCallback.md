## SendMessageCallback

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool SendMessageCallback(
   IntPtr hWnd,
   uint Msg,
   IntPtr wParam,
   IntPtr lParam,
   SendMessageDelegate lpResultCallBack,
   IntPtr dwData
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-sendmessagecallbacka)
