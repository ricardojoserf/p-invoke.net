## SetWindowPos

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool SetWindowPos(
   IntPtr hWnd,
   IntPtr hWndInsertAfter,
   int x,
   int y,
   int cx,
   int cy,
   uint uFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setwindowpos)
