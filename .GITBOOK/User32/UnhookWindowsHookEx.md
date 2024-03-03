## UnhookWindowsHookEx

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool UnhookWindowsHookEx(
   IntPtr hhk
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-unhookwindowshookex)
