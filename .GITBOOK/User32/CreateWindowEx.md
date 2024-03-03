## CreateWindowEx

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern IntPtr CreateWindowExA(uint dwExStyle,
   string lpClassName,
   string lpWindowName,
   uint dwStyle,
   int x,
   int y,
   int nWidth,
   int nHeight,
   IntPtr hWndParent,
   IntPtr hMenu,
   IntPtr hInstance,
   IntPtr lpParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-createwindowexa)
