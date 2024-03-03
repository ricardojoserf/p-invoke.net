## EnableMenuItem

```csharp
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool EnableMenuItem(
   IntPtr hMenu,
   uint uIDEnableItem,
   MenuFlags uEnable
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-enablemenuitem)
