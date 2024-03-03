## Findwindow

```
[DllImport("User32.dll")][return: MarshalAs(UnmanagedType.Bool)]
public static extern IntPtr FindWindow(string lpClassName,
   string lpWindowName
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-findwindoww)
