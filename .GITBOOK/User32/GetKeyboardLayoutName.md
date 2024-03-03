## GetKeyboardLayoutName

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Auto)]
public static extern bool GetKeyboardLayoutName(
   [Out] StringBuilder pwszKLID
);
```

Microsoft documentation: [Link](https://learn.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getkeyboardlayoutnamea)
