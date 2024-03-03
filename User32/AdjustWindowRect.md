## AdjustWindowRect

```csharp
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool AdjustWindowRect(
   ref RECT lpRect,
   uint dwStyle,
   [MarshalAs(UnmanagedType.Bool)] bool bMenu
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-adjustwindowrect)
