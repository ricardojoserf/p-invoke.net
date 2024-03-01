## DrawAnimatedRects

```
[DllImport("user32.dll", SetLastError = true)] [return: MarshalAs(UnmanagedType.Bool)]
public static extern bool DrawAnimatedRects(
   IntPtr hwnd,
   int idAni,
   ref RECT lprcFrom,
   ref RECT lprcTo
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-drawanimatedrects)
