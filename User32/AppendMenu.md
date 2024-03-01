## AppendMenu

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool AppendMenu(
   IntPtr hMenu,
   uint uFlags,
   uint uIDNewItem,
   string lpNewItem
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-appendmenua)
