## DefFrameProc

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DefFrameProcA(IntPtr hWnd,
   IntPtr hWndMDIClient,
   uint uMsg,
   IntPtr wParam,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-defframeproca)
