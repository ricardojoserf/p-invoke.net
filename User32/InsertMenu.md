## InsertMenu

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool InsertMenu(
   IntPtr hMenu,
   uint uPosition,
   uint uFlags,
   uint uIDNewItem,
   string lpNewItem
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-insertmenuw)
