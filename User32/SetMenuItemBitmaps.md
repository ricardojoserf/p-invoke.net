## SetMenuItemBitmaps

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool SetMenuItemBitmaps(
   IntPtr hMenu,
   uint uPosition,
   uint uFlags,
   IntPtr hBitmapUnchecked,
   IntPtr hBitmapChecked
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-setmenuitembitmapsw)
