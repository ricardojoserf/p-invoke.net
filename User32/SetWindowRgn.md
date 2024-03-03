## SetWindowRgn

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern int SetWindowRgn(
   IntPtr hWnd,
   IntPtr hRgn,
   bool bRedraw
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setwindowrgn)
