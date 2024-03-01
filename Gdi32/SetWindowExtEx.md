## SetWindowExtEx

```
[DllImport("gdi32.dll", SetLastError = true)]
public static extern bool SetWindowExtEx(
   IntPtr hdc,
   int x,
   int y,
   out SIZE lpsz
);
```

[Microsoft documentation](https://docs.microsoft.com/en-us/windows/win32/api/wingdi/nf-wingdi-setwindowextex)
