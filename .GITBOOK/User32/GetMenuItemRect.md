## GetMenuItemRect

```csharp
[DllImport("user32.dll")]
public static extern bool GetMenuItemRect(
   IntPtr hWnd,
   IntPtr hMenu,
   uint uItem,
   out RECT lprcItem
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getmenuitemrect)
