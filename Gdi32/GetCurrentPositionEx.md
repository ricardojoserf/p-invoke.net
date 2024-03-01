## GetCurrentPositionEx

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool GetCurrentPositionEx(
   IntPtr hdc,
   out POINT lppt
);
```

Microsoft documentation: [Link](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-getcurrentpositionex)
