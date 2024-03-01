## OpenDesktop

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr OpenDesktop(
   string lpszDesktop,
   uint dwFlags,
   bool fInherit,
   uint dwDesiredAccess
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-opendesktopw)
