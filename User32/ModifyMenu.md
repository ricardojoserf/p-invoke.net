## ModifyMenu

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool ModifyMenu(
   IntPtr hMnu,
   uint uPosition,
   uint uFlags,
   uint uIDNewItem,
   IntPtr lpNewItem
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-modifymenuw)
