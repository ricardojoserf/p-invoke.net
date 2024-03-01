## SetWindowOrgEx

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool SetWindowOrgEx(
   IntPtr hdc,
   int x,
   int y,
   out POINT lppt
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setwindoworgex)
