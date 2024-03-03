## GetMenuItemInfo

```csharp
[DllImport("user32.dll")]
public static extern bool GetMenuItemInfo(
   IntPtr hMenu,
   uint uItem,
   bool fByPosition,
   ref MENUITEMINFO lpmii
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getmenuiteminfoa)
