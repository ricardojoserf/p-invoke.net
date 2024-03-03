## SendMessageA

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern IntPtr SendMessageA(
   IntPtr hWnd,
   uint Msg,
   IntPtr wParam,
   StringBuilder lParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-sendmessagea)
