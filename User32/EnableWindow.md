## EnableWindow

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EnableWindow(
   IntPtr hWnd,
   [MarshalAs(UnmanagedType.Bool)] bool bEnable
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-enablewindow)
