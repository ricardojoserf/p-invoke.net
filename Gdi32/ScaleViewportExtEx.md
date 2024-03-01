## ScaleViewportExtEx

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool ScaleViewportExtEx(
   IntPtr hdc,
   int xn,
   int dx,
   int dy,
   int yn,
   int yd,
   out SIZE lpsz
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-scaleviewportextex)
