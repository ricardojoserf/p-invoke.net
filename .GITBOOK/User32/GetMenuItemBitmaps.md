## GetMenuItemBitmaps

```
[DllImport("user32.dll")]
public static extern bool GetMenuItemBitmaps(
   IntPtr hMenu,
   uint nIDFirst,
   uint nIDLast,
   out IntPtr hBmpUnchecked,
   out IntPtr hBmpChecked,
   uint fuFlags
);
```

