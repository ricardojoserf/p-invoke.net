## GetMenuBarInfo

```
[DllImport("user32.dll")]
public static extern bool GetMenuBarInfo(
   IntPtr hwnd,
   long idObject,
   long idItem,
   ref MENUBARINFO pmbi
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getmenubarinfo)
