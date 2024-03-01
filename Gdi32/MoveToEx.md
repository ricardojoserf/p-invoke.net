## MoveToEx

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool MoveToEx(
   IntPtr hdc,
   int x,
   int y,
   ref POINT lpPoint
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-movetoex)
