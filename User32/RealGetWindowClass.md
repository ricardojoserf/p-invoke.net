## RealGetWindowClass

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern uint RealGetWindowClass(
   IntPtr hwnd,
   [Out] StringBuilder pszType,
   uint cchType
);
```

[Microsoft documentation](TODO)
