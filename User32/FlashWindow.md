## FlashWindow

```csharp
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool FlashWindow(
   IntPtr hWnd,
   [MarshalAs(UnmanagedType.Bool)] bool bInvert
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-flashwindow)
