## EndPaint

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool EndPaint(
   IntPtr hWnd,
   [In] ref PAINTSTRUCT lpPaint
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-endpaint)
