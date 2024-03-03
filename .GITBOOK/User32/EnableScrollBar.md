## EnableScrollBar

```csharp
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnableScrollBar(
   IntPtr hWnd,
   uint wSBflags,
   uint wArrows
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-enablescrollbar)
