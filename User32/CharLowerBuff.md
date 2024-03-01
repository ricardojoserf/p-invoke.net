## CharLowerBuff

```
[DllImport("user32.dll", SetLastError = true, CharSet = CharSet.Unicode)]
public static extern uint CharLowerBuff(
   [In,
   Out] IntPtr lpsz,
   uint cchLength
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-charlowerbuffw)
