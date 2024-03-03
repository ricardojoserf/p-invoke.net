## FindWindowEx

```csharp
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern IntPtr FindWindowExA(IntPtr hWndParent,
   IntPtr hWndChildAfter,
   string lpszClass,
   string lpszWindow
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-findwindowexa)
