## EnumDesktopWindows

```csharp
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnumDesktopWindows(
   IntPtr hDesktop,
   EnumWindowsProc lpfn,
   IntPtr lParam
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-enumdesktopwindows)
