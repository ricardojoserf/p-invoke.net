## TileWindows

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool TileWindows(
   IntPtr hwndParent,
   uint wHow,
   [In] ref RECT lpRect,
   uint cKids,
   IntPtr lpKids
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-tilewindows)
