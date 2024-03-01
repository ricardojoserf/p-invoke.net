## SetMenuItemInfo

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern bool SetMenuItemInfo(
   IntPtr hMenu,
   uint uItem,
   bool fByPosition,
   ref MENUITEMINFO lpmii
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setmenuiteminfow)
