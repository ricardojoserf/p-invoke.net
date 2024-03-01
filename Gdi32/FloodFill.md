## FloodFill

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool FloodFill(
   IntPtr hdc,
   int nXStart,
   int nYStart,
   uint crColor
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-floodfill)
