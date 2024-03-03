## DefMDIChildProc

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr DefMDIChildProcA(IntPtr hWnd,
   uint uMsg,
   IntPtr wParam,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-defmdichildproca)
