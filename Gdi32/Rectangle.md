## Rectangle

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool Rectangle(
   IntPtr hdc,
   int left,
   int top,
   int right,
   int bottom
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-rectangle)
