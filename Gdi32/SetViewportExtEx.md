## SetViewportExtEx

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool SetViewportExtEx(
   IntPtr hdc,
   int x,
   int y,
   out SIZE lpsz
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setviewportextex)
