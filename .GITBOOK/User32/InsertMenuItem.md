## InsertMenuItem

```csharp
[DllImport("user32.dll", SetLastError = true)]
public static extern bool InsertMenuItem(
   IntPtr hmenu,
   uint item,
   bool fByPosition,
   [In] ref MENUITEMINFO lpmii
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-insertmenuitemw)
