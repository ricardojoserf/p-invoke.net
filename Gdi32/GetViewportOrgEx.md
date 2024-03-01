## GetViewportOrgEx

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetViewportOrgEx(
   IntPtr hdc,
   out POINT lpPoint
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getviewportorgex)
