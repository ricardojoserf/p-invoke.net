## OpenWindowStation

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr OpenWindowStation(
   string lpszWinSta,
   bool fInherit,
   uint dwDesiredAccess
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-openwindowstationw)
