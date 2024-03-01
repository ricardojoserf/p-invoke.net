## AlignRects

```
[DllImport("user32.dll", SetLastError = true)]
public static extern void AlignRects(
   ref RECT prcPrimary,
   ref RECT prcSecondary,
   uint dwFlags
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-alignrects)
