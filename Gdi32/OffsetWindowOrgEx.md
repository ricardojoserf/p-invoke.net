## OffsetWindowOrgEx

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool OffsetWindowOrgEx(
   IntPtr hdc,
   int nXOffset,
   int nYOffset,
   out POINT lpPoint
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-offsetwindoworgex)
