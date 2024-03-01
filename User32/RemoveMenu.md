## RemoveMenu

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool RemoveMenu(
   IntPtr hMenu,
   uint uPosition,
   uint uFlags
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-removemenu)
