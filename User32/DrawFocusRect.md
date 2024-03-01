## DrawFocusRect

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DrawFocusRect(
   IntPtr hDC,
   [In] ref RECT lprc
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-drawfocusrect)
