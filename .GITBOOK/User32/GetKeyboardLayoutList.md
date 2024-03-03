## GetKeyboardLayoutList

```csharp
[DllImport("user32.dll")]
public static extern int GetKeyboardLayoutList(
   int nBuff,
   [Out] IntPtr[] lpList
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-getkeyboardlayoutlist)
