## Rectangle

```
[DllImport("coredll.dll", SetLastError = true)]
public static extern bool Rectangle(
   IntPtr hdc,
   int nLeftRect,
   int nTopRect,
   int nRightRect,
   int nBottomRect
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-rectangle)
