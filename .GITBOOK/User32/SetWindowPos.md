## SetWindowPos

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool SetWindowPos(
   IntPtr hWnd,
   IntPtr hWndInsertAfter,
   int X,
   int Y,
   int cx,
   int cy,
   uint uFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setwindowpos)
