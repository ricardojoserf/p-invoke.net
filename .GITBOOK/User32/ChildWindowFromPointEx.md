## ChildWindowFromPointEx

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr ChildWindowFromPointEx(
   IntPtr hwnd,
   POINT pt,
   uint flags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-childwindowfrompointex)
