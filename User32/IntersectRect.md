## IntersectRect

```
[DllImport("user32.dll", SetLastError = true)]
public static extern bool IntersectRect(
   out RECT lprcDst,
   in RECT lprcSrc1,
   in RECT lprcSrc2
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-intersectrect)
