## AdjustWindowRectEx

```csharp
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool AdjustWindowRectEx(
   ref RECT lpRect,
   uint dwStyle,
   [MarshalAs(UnmanagedType.Bool)] bool bMenu,
   uint dwExStyle
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-adjustwindowrectex)
