## TrackPopupMenuEx

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool TrackPopupMenuEx(
   IntPtr hMenu,
   uint fuFlags,
   int x,
   int y,
   IntPtr hwnd,
   IntPtr lptpm
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-trackpopupmenuex)
