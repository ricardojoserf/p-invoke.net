## GetMenuInfo

```csharp
[DllImport("user32.dll")]
public static extern bool GetMenuInfo(
   IntPtr hmenu,
   ref MENUINFO lpcmi
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getmenuinfo)
