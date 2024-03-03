## SetScrollInfo

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern int SetScrollInfo(
   IntPtr hwnd,
   int fnBar,
   [In] ref SCROLLINFO lpsi,
   bool fRedraw
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setscrollinfo)
