## AppendMenu

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool AppendMenu(
   IntPtr hMenu,
   MenuFlags uFlags,
   uint uIDNewItem,
   string lpNewItem
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-appendmenuw)
