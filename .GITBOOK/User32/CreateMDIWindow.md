## CreateMDIWindow

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Ansi)]
public static extern IntPtr CreateMDIWindowA(string lpClassName,
   string lpWindowName,
   uint dwStyle,
   int X,
   int Y,
   int nWidth,
   int nHeight,
   IntPtr hWndParent,
   IntPtr hInstance,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-createmdiwindowa)
