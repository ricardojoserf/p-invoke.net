## CheckWindowThreadDesktop

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool CheckWindowThreadDesktop(
   uint idThread,
   [MarshalAs(UnmanagedType.LPWStr)] string lpszDesktop
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-checkwindowthreaddesktop)
