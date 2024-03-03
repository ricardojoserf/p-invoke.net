## GetScrollBarInfo

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool GetScrollBarInfo(
   IntPtr hwnd,
   uint idObject,
   ref SCROLLBARINFO psbi
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getscrollbarinfo)
