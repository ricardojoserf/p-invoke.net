## GetNextWindow

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr GetNextWindow(
   IntPtr hWnd,
   uint wCmd
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getnextwindow)
