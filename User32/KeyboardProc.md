## KeyboardProc

```
[DllImport("user32.dll", SetLastError = true)]
public static extern IntPtr KeyboardProc(
   int code,
   IntPtr wParam,
   IntPtr lParam
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-keyboardproc)
